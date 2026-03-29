# Software Requirements Specification (SRS)

**Generated:** 2026-03-29 15:06:55
**Total Requirements:** 13
**Requirement Groups:** 9

---

## Table of Contents

- **REQ-001: Receive Email Notifications** [HIGH] (2 req)
- **REQ-002: Handle Payment Processing** [HIGH] (2 req)
- **REQ-003: Cluster 3** [HIGH] (2 req)
- **REQ-004: Load Dashboard** [HIGH] (2 req)
- **REQ-005: Export Reports** [HIGH] (1 req)
- **REQ-006: Offline Support** [HIGH] (1 req)
- **REQ-007: Support Login Page** [HIGH] (1 req)
- **REQ-008: Audit Logs** [HIGH] (1 req)
- **REQ-009: User Passwords** [HIGH] (1 req)

---

## REQ-001: Receive Email Notifications

**Priority:** 🔴 HIGH
**Summary:** Customers should receive email notifications when orders are shipped. The checkout flow needs to be more reliable during sales events.
**Analysis:** Cluster 'Receive Email Notifications' contains 2 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-001.1:** Customers should receive email notifications when orders are shipped.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | Customers |
| **Action** | receive |
| **Feature** | email notifications |
| **Constraint** | when orders are |
| **Priority Indicator** | should |

> **Canonical:** Customers shall receive email notifications when orders are.

**Priority: HIGH** | Confidence: 59.8%
  - Elevated priority due to explicit indicator: 'should' (+5)
  - Medium importance due to expected requirement ('should') (+0.5)

**REQ-001.2:** The checkout flow needs to be more reliable during sales events.

*Type: 📊 Non-Functional*

| Attribute | Value |
|-----------|-------|
| **Feature** | checkout flow |
| **Constraint** | during sales events |
| **Priority Indicator** | needs to |

> **Canonical:** The system shall checkout flow during sales events.

**Priority: HIGH** | Confidence: 58.5%
  - Elevated priority due to explicit indicator: 'needs to' (+5)

---

## REQ-002: Handle Payment Processing

**Priority:** 🔴 HIGH
**Summary:** The system must handle payment processing within 2 seconds. The payment gateway must support multiple currencies.
**Analysis:** Cluster 'Handle Payment Processing' contains 2 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-002.1:** The system must handle payment processing within 2 seconds.

*Type: 📊 Non-Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | The system |
| **Action** | handle |
| **Feature** | payment processing |
| **Constraint** | within 2 seconds |
| **Priority Indicator** | must |

> **Canonical:** The system shall handle payment processing within 2 seconds.

**Priority: HIGH** | Confidence: 62.4%
  - Elevated priority due to explicit indicator: 'must' (+5)
  - Contains critical time constraints: 'within 2 seconds' (+2)
  - High importance due to mandatory requirement ('must') (+1)

**REQ-002.2:** The payment gateway must support multiple currencies.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | The payment gateway |
| **Action** | support |
| **Feature** | currencies |
| **Priority Indicator** | must |

> **Canonical:** The payment gateway shall support currencies.

**Priority: HIGH** | Confidence: 62.2%
  - Elevated priority due to explicit indicator: 'must' (+5)
  - High importance due to mandatory requirement ('must') (+1)

---

## REQ-003: Cluster 3

**Priority:** 🔴 HIGH
**Summary:** Users are complaining that login is too slow during peak hours. We should improve login speed.
**Analysis:** Cluster 'Cluster 3' contains 2 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-003.1:** Users are complaining that login is too slow during peak hours.

*Type: 📊 Non-Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | Users |
| **Action** | login |
| **Constraint** | during peak hours |
| **Priority Indicator** | are complaining that |

> **Canonical:** Users shall login during peak hours.

**Priority: HIGH** | Confidence: 57.8%
  - Elevated priority due to explicit indicator: 'are complaining that, is too' (+5)
  - User pain point identified showing negative sentiment: 'complaining, slow' (+4)

**REQ-003.2:** We should improve login speed.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Action** | improve |
| **Priority Indicator** | We |

> **Canonical:** The system shall improve.

**Priority: HIGH** | Confidence: 56.2%
  - Elevated priority due to explicit indicator: 'We, should' (+5)
  - Medium importance due to expected requirement ('should') (+0.5)

---

## REQ-004: Load Dashboard

**Priority:** 🔴 HIGH
**Summary:** The dashboard must load within 3 seconds. The search functionality should return results in under 1 second.
**Analysis:** Cluster 'Load Dashboard' contains 2 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-004.1:** The dashboard must load within 3 seconds.

*Type: 📊 Non-Functional*

| Attribute | Value |
|-----------|-------|
| **Action** | load |
| **Feature** | dashboard |
| **Constraint** | within 3 seconds |
| **Priority Indicator** | must |

> **Canonical:** The system shall load dashboard within 3 seconds.

**Priority: HIGH** | Confidence: 58.7%
  - Elevated priority due to explicit indicator: 'must' (+5)
  - Contains critical time constraints: 'within 3 seconds' (+2)
  - High importance due to mandatory requirement ('must') (+1)

**REQ-004.2:** The search functionality should return results in under 1 second.

*Type: 📊 Non-Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | The search |
| **Action** | return |
| **Feature** | results |
| **Constraint** | in under 1 second |
| **Priority Indicator** | should |

> **Canonical:** The search shall return results in under 1 second.

**Priority: HIGH** | Confidence: 62.2%
  - Elevated priority due to explicit indicator: 'should' (+5)
  - Contains critical time constraints: 'in under 1 second' (+2)
  - Medium importance due to expected requirement ('should') (+0.5)

---

## REQ-005: Export Reports

**Priority:** 🔴 HIGH
**Summary:** Users must be able to export reports as PDF.
**Analysis:** Cluster 'Export Reports' contains 1 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-005.1:** Users must be able to export reports as PDF.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | Users |
| **Action** | export |
| **Feature** | reports |
| **Constraint** | as PDF. |
| **Priority Indicator** | must |

> **Canonical:** Users shall export reports as PDF.

**Priority: HIGH** | Confidence: 61.0%
  - Elevated priority due to explicit indicator: 'must' (+5)
  - High importance due to mandatory requirement ('must') (+1)

---

## REQ-006: Offline Support

**Priority:** 🔴 HIGH
**Summary:** The mobile app needs to work offline without data loss.
**Analysis:** Cluster 'Offline Support' contains 1 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-006.1:** The mobile app needs to work offline without data loss.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | The mobile app |
| **Action** | work |
| **Constraint** | offline |
| **Constraint** | without data loss |
| **Priority Indicator** | needs to |

> **Canonical:** The mobile app shall work offline, without data loss.

**Priority: HIGH** | Confidence: 59.9%
  - Elevated priority due to explicit indicator: 'needs to' (+5)
  - High risk impact word detected: 'data loss' (+4)

---

## REQ-007: Support Login Page

**Priority:** 🔴 HIGH
**Summary:** The login page must support single sign-on via OAuth.
**Analysis:** Cluster 'Support Login Page' contains 1 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-007.1:** The login page must support single sign-on via OAuth.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | OAuth |
| **Action** | support |
| **Feature** | login page |
| **Constraint** | on |
| **Priority Indicator** | must |

> **Canonical:** OAuth shall support login page on.

**Priority: HIGH** | Confidence: 62.5%
  - Elevated priority due to explicit indicator: 'must' (+5)
  - High importance due to mandatory requirement ('must') (+1)

---

## REQ-008: Audit Logs

**Priority:** 🔴 HIGH
**Summary:** Admin users need urgent access to the audit logs.
**Analysis:** Cluster 'Audit Logs' contains 1 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-008.1:** Admin users need urgent access to the audit logs.

*Type: ⚙️ Functional*

| Attribute | Value |
|-----------|-------|
| **Actor** | Admin |
| **Feature** | audit logs |
| **Priority Indicator** | need urgent access |

> **Canonical:** Admin shall audit logs.

**Priority: HIGH** | Confidence: 60.8%
  - Elevated priority due to explicit indicator: 'need urgent access' (+5)
  - High importance due to mandatory requirement ('need') (+1)

---

## REQ-009: User Passwords

**Priority:** 🔴 HIGH
**Summary:** It is critical that user passwords are encrypted at all times.
**Analysis:** Cluster 'User Passwords' contains 1 requirement(s) grouped by semantic similarity. Cluster priority: HIGH. Clustering quality (silhouette): 0.15 (weak).

### Requirements

**REQ-009.1:** It is critical that user passwords are encrypted at all times.

*Type: 📊 Non-Functional*

| Attribute | Value |
|-----------|-------|
| **Feature** | user passwords |
| **Constraint** | at all times |
| **Priority Indicator** | It |

> **Canonical:** The system shall user passwords at all times.

**Priority: HIGH** | Confidence: 61.5%
  - Elevated priority due to explicit indicator: 'It, is critical that' (+5)

---

## Limitations & Future Improvements

While the current pipeline demonstrates a functional end-to-end AI Requirements Engineering system, there are several avenues for future enhancement:

- **Clustering Algorithms:** The current Agglomerative approach works well for small datasets. For larger corpora, transitioning to **BERTopic** would provide dynamic, topic-aware groupings.
- **NER Accuracy:** The Named Entity Recognition model is currently trained on a highly restricted dataset. Expanding this dataset with diverse domain-specific requirements will dramatically improve boundary detection and recall.
- **Real-time Integration:** The system currently processes static text chunks. Future iterations should integrate with **Jira, Slack, or Trello APIs** to pull requirements dynamically and log structured outputs directly into project management tools.
- **Advanced Prioritization:** Currently, prioritization is driven by a rule-based multi-signal engine. Transitioning to a **learning-based model** (e.g., fine-tuning a transformer on historical project priority data) would yield more nuanced and context-aware scoring.

---
