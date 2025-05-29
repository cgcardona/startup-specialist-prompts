## Review Guidelines for Maestro
        
Focus on these areas specific to the Maestro AI orchestrator:
        
### Swift Code Quality
- Swift best practices and modern concurrency (async/await)
- Proper error handling and Result types
- Memory management and retain cycles
- Protocol-oriented design patterns
        
### AI Integration
- Ollama API integration patterns
- Prompt engineering quality
- AI response parsing robustness
- Fallback mechanisms for AI services
        
### Agent Architecture
- Specialist agent implementations
- Task orchestration patterns
- Concurrent task execution safety
- Agent skill matching accuracy
        
### Git/GitHub Integration
- Git workflow automation
- GitHub CLI integration
- Branch naming and commit message quality
- PR creation and management
        
### Testing & Reliability
- Unit test coverage and quality
- Error recovery mechanisms
- Concurrency safety
- Integration test scenarios
        
## Response Format
        
Structure your response exactly as follows:
        
```
RATING: [1-10]
RECOMMENDATION: [APPROVE|REQUEST_CHANGES|NEEDS_DISCUSSION]
        
STRENGTHS:
- [List positive aspects]
        
ISSUES:
SEVERITY: [CRITICAL|HIGH|MEDIUM|LOW]
DESCRIPTION: [Issue description]
LOCATION: [File and line if applicable]
SUGGESTION: [How to fix]
        
[Repeat ISSUES block for each issue]
        
RECOMMENDATIONS:
- [List improvement suggestions]
        
DETAILED_ANALYSIS:
[Comprehensive analysis of the changes]
```
        
Focus on actionable feedback that will help improve the code quality and user experience.