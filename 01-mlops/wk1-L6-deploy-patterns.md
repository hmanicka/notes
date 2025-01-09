# Deploying Machine Learning Systems

## 1. **Deployment Isn't "Set and Forget"**
   - Deploying a learning algorithm requires careful consideration to prevent failures.
   - Different use cases and deployment patterns exist based on the context.

---

## 2. **Common Deployment Use Cases**
   - **New Product or Capability**: Gradually ramp up traffic to test performance.
   - **Automating or Assisting Existing Tasks**: Example: Replacing human inspections with ML, leveraging patterns like shadow mode.
   - **Upgrading an Existing ML System**: Replace with a better version while minimizing risk.

---

## 3. **Key Deployment Patterns**
### A. **Shadow Mode Deployment**
   - **Description**: The ML system runs alongside humans or older systems but doesn’t make real decisions.
   - **Use Case**: Gather performance data without affecting real operations.
   - **Example**: Smartphone defect inspections where ML predictions are compared to human judgments.

### B. **Canary Deployment**
   - **Description**: Start with a small fraction of traffic, monitor results, and gradually increase usage.
   - **Use Case**: Minimize risks by testing ML in live scenarios on limited traffic.
   - **Reference**: Named after "canary in a coal mine" to detect problems early.

### C. **Blue-Green Deployment**
   - **Description**: Maintain two systems—one old (blue) and one new (green). Switch traffic gradually or all at once to the new system.
   - **Use Case**: Allows rollback to the old system if issues arise.
   - **Example**: Transitioning visual inspection systems.

---

## 4. **Degrees of Automation**
   - Deployment isn’t binary (deploy vs. not deploy); instead, consider the **degree of automation**:
     1. **Human-Only System**: No automation.
     2. **Shadow Mode**: ML generates predictions without affecting operations.
     3. **AI Assistance**: Highlights areas of concern for human review.
     4. **Partial Automation**: ML makes decisions when confident; humans handle uncertain cases.
     5. **Full Automation**: ML makes all decisions.

   - **Key Concept**: Many real-world applications (e.g., factories) may benefit from **human-in-the-loop deployments** rather than full automation.

---

## 5. **Monitoring and Rollback**
   - Always monitor ML systems to detect and address issues early.
   - Implement rollback mechanisms to revert to previous systems if necessary.

---

## 6. **Choosing the Right Deployment Strategy**
   - Consider the application needs and system performance.
   - Start with less automation and incrementally increase as confidence grows.

---

## 7. **Human-In-The-Loop Systems**
   - Balance between AI assistance and full automation based on feasibility and requirements.
   - Ideal for contexts where ML performance isn’t reliable enough for full automation.

---

## 8. **Consumer Applications vs. Industrial Use**
   - **Consumer Internet Applications**: Often require full automation (e.g., web search).
   - **Industrial Applications**: Human in the loop automation.
