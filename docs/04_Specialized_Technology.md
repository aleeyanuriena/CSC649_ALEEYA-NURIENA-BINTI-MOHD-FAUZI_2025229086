
# 4.0 Specialized Technology

## 4.1 Fundamental Concepts (C1)

### 4.1.1 What is Rule-Based Expert System?

A Rule-Based Expert System is a type of artificial intelligence (AI) that uses predefined IF–THEN rules to make decisions based on specific conditions. Unlike machine learning, which learns from training data, a rule-based expert system applies rules defined by human knowledge or expertise.

The system consists of a knowledge base that stores rules and an inference engine that evaluates information against those rules to produce decisions.

In the proposed UiTM uFuture enhancement, this technology is used to classify assignment priorities based on deadlines and submission statuses. For example, IF an assignment is pending and due within two days, THEN it is classified as High Priority. This helps students identify urgent tasks and manage their academic activities more effectively.

### 4.1.2 Key Concepts of Rule-Based Expert System

A Rule-Based Expert System consists of four main components:

1. **Knowledge Base:** Stores predefined IF–THEN rules used to classify assignment priorities.
2. **Inference Engine:** Evaluates assignment information against the rules in the knowledge base to determine the appropriate priority.
3. **Working Memory:** Stores assignment information, including deadlines, submission statuses, and remaining days.
4. **User Interface:** Displays the priority classifications on the proposed Academic Dashboard.

### 4.1.3 How Rule-Based Expert System Works

A Rule-Based Expert System works by evaluating input information against predefined IF–THEN rules. In the proposed uFuture enhancement, assignment deadlines and submission statuses are stored as facts in working memory. The inference engine then checks these facts against the rules in the knowledge base to determine the appropriate classification.

For example, submitted assignments are classified as Completed, while pending assignments with passed deadlines are classified as Overdue. Pending assignments due within two days receive High Priority, those due within three to five days receive Medium Priority, and those with more than five days remaining receive Low Priority.

The classification results are displayed on the proposed Academic Dashboard to help students identify urgent assignments.

**Figure 4.1: Proposed Rule-Based Expert System Architecture for Assignment Priority Classification**

<!-- Insert the architecture diagram image here after uploading it to GitHub. -->
