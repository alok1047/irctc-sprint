# Impact vs Effort Matrix

|                   | Low Effort | High Effort |
|-------------------|------------|-------------|
| High Impact | Smart Search Filters, Delay Notification | Tatkal Queue, Waitlist Predictor |
| Low Impact | Passenger Autofill | Payment Recovery |

---

## Placement Justifications

### Tatkal Queue
High impact because millions use Tatkal.
High effort because backend queue infrastructure is required.
Should be prioritized as a major project.

### Waitlist Predictor
High impact because users depend on confirmation chances.
Requires ML infrastructure.
Major project.

### Smart Search Filters
Easy implementation.
Improves search experience.
Quick win.

### Delay Notification
Simple integration.
Benefits many users.
Quick win.

### Payment Recovery
Complex backend coordination.
Moderate impact.
Lower priority.

### Passenger Autofill
Easy implementation.
Limited impact.
Can be done later.

---

## Recommended Sprint Order

1. Smart Search Filters
2. Delay Notification
3. Tatkal Queue
4. Waitlist Predictor
5. Passenger Autofill
6. Payment Recovery