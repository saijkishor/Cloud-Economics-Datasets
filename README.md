## 📣 Community Call: Contribute Real-World Datasets for Cloud Economics Education

We’re building an open repository of **real-world, privacy-safe datasets** to support education and benchmarking in cloud economics. If you’ve run workloads on AWS, Azure, GCP, or OCI and can share anonymised traces, your contribution can help learners and researchers understand the cost-performance dynamics of cloud-native systems.

---

## 🎯 Target Usage Scenarios

We’re looking for datasets that illustrate:

| Concept                     | Example Scenario                                      |
|----------------------------|-------------------------------------------------------|
| Cost-performance tradeoffs | Comparing EC2 instance types under ML inference load |
| Elasticity and autoscaling | Horizontal scaling during traffic spikes             |
| Spot pricing volatility    | Spot instance interruptions and recovery             |
| Resource scheduling        | Kubernetes pod placement and cost impact             |
| Storage/network economics  | EBS vs S3 cost behavior under read/write patterns    |

---

## 🛠️ Reliable Techniques for Data Collection

Please use **real monitoring and billing tools** from your cloud provider:

- **AWS**: CloudWatch, Cost Explorer, CUR (Cost and Usage Report)
- **Azure**: Monitor, Cost Management + Billing
- **GCP**: Operations Suite, Billing Export to BigQuery
- **OCI**: Monitoring and Cost Analysis

> ⚠️ Only include metrics you’ve personally collected from actual workloads.  
> ❌ No synthetic or simulated data, please.

---

## ✅ Privacy and Compliance Guidelines

To protect privacy and ensure ethical sharing:

- ❌ Do **not include** IP addresses, usernames, internal hostnames, or customer identifiers
- ✅ Do **include** timestamps, resource types, usage metrics, and cost data
- ✅ Add a short note describing the workload and context  
  _e.g, “ML inference service on GCP with autoscaling”_

All submissions are reviewed before publication. Datasets will be shared under a **permissive license (e.g., CC BY)** for educational use only.

---

## 📊 Minimum Dataset Requirements

To ensure experiments are meaningful:

- **Minimum rows**: 500–1,000 entries
- **Required fields** (at least 3):
  - Timestamp or time interval
  - Resource usage (CPU, memory, IOPS, etc.)
  - Cost (per unit or total)
  - Instance type or resource ID
  - Event type (e.g., scale-up, termination)

**Optional fields**:
- Region/zone
- Pricing model
- SLA violations
- Network/storage metrics

---

## 📤 Submit Your Dataset Anonymously

Privacy Note:
When you upload a file via this form, Google will record your name, email address, and profile photo. This information is visible only to the form owner and will be used solely for attribution and compliance review. We do not share contributor identities publicly without consent.

Use our privacy-safe Google Form:  
👉 [https://forms.gle/TR2qGcbTg5UVUh9w6]

You can optionally be credited via **pseudonym or GitHub handle**.  
All datasets will be curated and published for educational benchmarking.


---

_Thank you for helping build a transparent, reproducible, and community-powered cloud economics knowledge base._
