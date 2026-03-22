# Black Mode — TODO

## [RC] Core Engine
- [ ] [RC] Implement Ollama model routing layer (fast/code/reasoning/review)
- [ ] [RC] Build intent classifier for automatic model selection
- [ ] [RC] Add Tree-sitter parsing for multi-language context extraction
- [ ] [RC] Implement GGUF quantization pipeline for custom models
- [ ] [RC] Build hardware detection module (Hailo-8, GPU, CPU fallback)

## [RC] Context Engine
- [ ] [RC] Integrate Qdrant vector store for codebase indexing
- [ ] [RC] Build nomic-embed-text embedding pipeline
- [ ] [RC] Implement incremental index updates on file change
- [ ] [RC] Add dependency graph resolution for context window assembly
- [ ] [RC] Build FTS5 audit log with cryptographic session signing

## [RC] Terminal Interface
- [ ] [RC] Build TUI with Ratatui (Rust terminal framework)
- [ ] [RC] Implement streaming response rendering
- [ ] [RC] Add inline diff visualization for code suggestions
- [ ] [RC] Build command palette with fuzzy search
- [ ] [RC] Add pipe-friendly output mode for scripting

## [RC] Git Integration
- [ ] [RC] Auto-generate commit messages from staged diffs
- [ ] [RC] Generate PR descriptions with context-aware summaries
- [ ] [RC] Build code review agent (security, performance, style)
- [ ] [RC] Integrate with Gitea webhooks for automated review
- [ ] [RC] Add branch strategy awareness for contextual suggestions

## [RC] Security & Privacy
- [ ] [RC] Implement zero-outbound network verification
- [ ] [RC] Build DNS-level monitoring for data exfiltration detection
- [ ] [RC] Add Ed25519 session signing for audit trail integrity
- [ ] [RC] Create compliance report generator (SOC2 format)
- [ ] [RC] Implement encrypted local model cache

## [RC] Distribution
- [ ] [RC] Build Homebrew formula (blackroad/tap/black-mode)
- [ ] [RC] Create curl installer script
- [ ] [RC] Package for Debian/Ubuntu (.deb)
- [ ] [RC] Package for Arch Linux (AUR)
- [ ] [RC] Build Docker image for containerized usage
