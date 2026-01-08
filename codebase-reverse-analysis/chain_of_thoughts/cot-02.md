I'm taking over this codebase and need COMPLETE understanding for production ownership.

**PHASE 1: OPERATIONAL READINESS (HIGHEST PRIORITY)**
1. **Infrastructure & Deployment**
   - How is this deployed? (containers, VMs, serverless?)
   - Document CI/CD pipeline
   - Environment configurations (dev, staging, prod)
   - Infrastructure as code analysis
   - Deployment procedures and rollback steps
   
2. **Operations & Monitoring**
   - How to access logs and where they're stored
   - What monitoring/alerting exists
   - Document health check endpoints
   - List all dashboards and their purposes
   - Incident response procedures
   - Backup and restore procedures
   
3. **External Dependencies**
   - All third-party integrations with details
   - Rate limits and quotas
   - Fallback strategies
   - Authentication mechanisms
   - Cost implications

**PHASE 2: RUNTIME & PERFORMANCE**
4. **Runtime Behavior Analysis**
   - Identify performance bottlenecks from code
   - Connection pool configurations
   - Resource usage patterns (memory, CPU indicators)
   - Caching strategy
   - Transaction boundaries
   - Async vs sync operations
   - Retry logic and circuit breakers

5. **Observability**
   - What logs are generated and at what levels
   - What metrics are collected
   - Tracing instrumentation
   - Correlation ID usage
   - Error tracking setup

**PHASE 3: CODE & ARCHITECTURE (Your Current Strength)**. 
6. **System Architecture**
   - Logical layers with C4 diagram
   - Component relationships
   - Technology stack

7. **Database Deep Dive**
   - Complete ERD with constraints
   - Indexes and performance considerations
   - Migration history

8. **Business Domain**
   - Domain model and glossary
   - Business rules
   - End-to-end flows

9. **Data Governance**
   - Data lineage (where data comes from/goes to)
   - PII and sensitive data locations
   - Data retention policies
   - Compliance requirements (GDPR, etc.)

10. **Security Posture**
    - Authentication/authorization implementation
    - Secret management
    - Known vulnerabilities
    - Security best practices compliance

11. **UI Inventory**
    - All screens with purposes
    - Navigation flows
    - Screen-to-API mappings

Save ALL findings to appropriate wiki/ folders with Mermaid diagrams.
Prioritize documentation that helps me keep the system running.