# AI-Assisted Web Development Support Hub

![Project Architecture](https://mermaid.ink/svg/eyJjb2RlIjoiZ3JhcGggVERcbiAgQVtBSS1Bc3Npc3RlZCBJREUgKFdpbmRzdXJmKV0gLS0-IEJbRnJvbnRlbmQ6IFJlYWN0L1RhaWx3aW5kL1R5cGVTY3JpcHRdXG4gIEIgLS0-IENbQmFja2VuZDogU3VwYWJhc2VdXG4gIEMgLS0-IERbRGVwbG95bWVudDogVmVyY2VsXVxuICBEIC0tPiBFW0xpdmUgUHJvZHVjdGlvbl0iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)

## About This Project

This repository serves as the central hub for supporting multiple AI-assisted web projects built with modern technologies. The primary focus is providing development expertise where AI tools reach their limits, particularly in:

1. **Debugging Complex Issues**: Addressing edge cases where AI-generated code fails in production (e.g., Supabase row-level security misconfigurations, React hook dependencies)

2. **Deployment Optimization**: Solving Vercel deployment challenges like:
   - Environment variable management
   - Serverless function cold starts
   - Proper caching headers for dynamic content

3. **Architecture Guidance**: Recommending improvements to AI-generated structures, such as:
   - Efficient data fetching patterns (SWR vs React Query)
   - Supabase storage optimization strategies
   - Authentication flow enhancements

## Technical Challenges Addressed

### Common Pain Points

1. **AI-Generated Code Limitations**:
   - Component re-rendering issues due to improper memoization
   - TypeScript type inference gaps in generated code
   - Asynchronous state management anti-patterns

2. **Supabase-Specific Issues**:
   - Realtime subscription memory leaks
   - JWT refresh token handling
   - Bulk insert performance optimization

3. **Vercel Deployment Quirks**:
   - Edge Function vs Serverless Function tradeoffs
   - Proper ISR configuration for dynamic routes
   - Handling CORS in serverless environments

## Development Approach

The support methodology follows three phases:

1. **Triage**:
   - Reproduce reported issues in isolated environments
   - Analyze Windsurf-generated code for common antipatterns
   - Check Supabase logs for RLS policy violations

2. **Solution Design**:
   - Propose multiple solutions with tradeoff analysis
   - Implement least-disruptive fixes first
   - Document architectural decisions

3. **Knowledge Transfer**:
   - Create annotated code samples
   - Record short Loom explanations
   - Maintain troubleshooting playbook

## Technology Stack

| Component       | Technology               | Version  | Purpose                          |
|-----------------|--------------------------|----------|----------------------------------|
| Frontend        | React + TypeScript       | 18.2+    | Core application framework       |
| Styling         | Tailwind CSS             | 3.3+     | Utility-first CSS                |
| Backend         | Supabase                 | 2.0+     | Database/auth/storage            |
| Deployment      | Vercel                   | -        | Serverless hosting               |
| Development     | Windsurf AI              | -        | AI-assisted coding               |

## Getting Support

For efficient troubleshooting, please provide:
1. Relevant code snippets with context
2. Exact error messages
3. Steps to reproduce
4. Screenshots of unexpected behavior
5. Windsurf prompt history (when applicable)
