# Key Challenges

## Overview
Deploying a machine learning model is a critical milestone in any project. However, it presents two primary challenges:
1. **Machine Learning/Statistical Issues**
2. **Software Engineering Issues**

---

## 1. Machine Learning/Statistical Issues
### **Concept Drift & Data Drift**
- **Concept Drift**: The relationship between input (X) and output (Y) changes.
  - Example: A house price model where inflation increases house prices without changes in house size.
- **Data Drift**: The distribution of input data (X) changes, but the relationship between X and Y remains stable.
  - Example: New microphone technology alters audio characteristics.

### **Types of Drift**
- **Gradual Changes**: Slow changes like language evolution with new vocabulary.
- **Sudden Shifts**: Abrupt changes in behavior or environment.
  - Example: COVID-19 dramatically changed credit card usage patterns.

### **Best Practices for Handling Drift**
- Regularly evaluate your model on **recent datasets** (e.g., data from the last few months).
- Use **validation sets** to monitor for performance degradation.
- Continuously collect and retrain on updated data to adapt to changes.

---

## 2. Software Engineering Issues
### **Checklist for Deployment**
- **Real-time vs. Batch Predictions**:
  - Real-time: Response within milliseconds (e.g., speech recognition).
  - Batch: Overnight processing (e.g., healthcare analytics).

- **Deployment Location**:
  - **Cloud**: High compute resources for complex tasks.
  - **Edge**: Independence from internet (e.g., factory systems).
  - **Browser**: Lightweight models deployed directly in browsers.

- **Compute Resource Management**:
  - Optimize for available CPU/GPU/memory resources.
  - Compress models if necessary for deployment.

- **Latency & Throughput**:
  - **Latency**: Time per prediction (e.g., <500 ms for speech recognition).
  - **Throughput**: Queries per second (QPS) the system must handle.

- **Logging**:
  - Log data for debugging, performance monitoring, and retraining.

- **Security & Privacy**:
  - Design for appropriate security levels based on sensitivity (e.g., healthcare data).

---

## Key Takeaways
1. **Initial Deployment vs. Maintenance**:
   - Initial deployment is just the beginning.
   - Continuous monitoring and updates are essential to adapt to changes in data.

2. **Design Patterns**:
   - Common deployment patterns vary across industries.
   - Choose the pattern that suits your application needs (covered in subsequent discussions).

---

## Visual Summary
1. **Drift**:
   - 🟢 Gradual: Slow change (e.g., language).
   - 🔴 Sudden: Rapid change (e.g., pandemic behavior).
2. **Deployment Considerations**:
   - Real-time vs Batch
   - Cloud vs Edge
   - Compute & Latency Needs
3. **Lifecycle**:
   - Deployment is halfway; maintenance ensures longevity.

