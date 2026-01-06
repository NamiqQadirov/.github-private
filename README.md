# Organization Custom Copilot Agents

## Available Agents

### @android-expert
Expert in Android development with Kotlin and Jetpack Compose
- Use for: Feature implementation, architecture questions
- Tools: Full access to read, search, edit

### @android-tester
Specialized in writing Android tests
- Use for: Creating unit tests, UI tests, test strategies
- Tools: Read and search only

### @android-reviewer
Code review specialist for Android apps
- Use for: PR reviews, code quality checks
- Tools: Read and search only

### @android-security
Security expert for Android applications
- Use for: Security reviews, vulnerability assessment
- Tools: Read and search only

## Usage in Android Studio

1. Open Copilot Chat
2. Type `@agent-name` followed by your question
3. Example: `@android-expert implement a login screen with MVVM`

## Request New Agents

Submit a PR to this repository with:
- Agent profile in `/agents/your-agent.md`
- Description of use case
- Required tools and model
```

**7.2 Announce to Team**

Send a message to your team:
```
🎉 Custom Copilot Agents Now Available!

We've created organization-level Copilot agents to help with Android development:

- @android-expert - For implementation and architecture
- @android-tester - For writing tests
- @android-reviewer - For code reviews
- @android-security - For security checks

How to use in Android Studio:
1. Update to latest Copilot plugin
2. Enable "Show organization agents" in settings
3. Use @agent-name in Copilot Chat

Docs: [link to .github-private repo]
Questions: #android-dev-help
```

## Using Agents in Android Studio

### Method 1: Direct Invocation
```
@android-expert Create a Room database entity for User with id, name, email, and created_at fields
```

### Method 2: In Code Reviews
When reviewing PRs, use:
```
@android-reviewer Review this ViewModel for potential issues
```

### Method 3: Pair Programming
```
@android-expert I need to implement offline-first sync. What's the best approach with Room and WorkManager?
