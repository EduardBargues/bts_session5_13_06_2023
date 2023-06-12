---
marp: true
theme: uncover
paginate: true
header: Cloud & Devops - Eduard Bargués
footer: Barcelona Technology School S.L.
# **class: invert**
# **color: Set text color**
# **backgroundColor**
---

<!--
_class: invert
-->

# **Cloud and DevOps**

1. Hello Cloud
2. Software development
3. AWS & Serverless
4. Security in AWS
5. 👉 **Security, Testing & Cost management** 👈
6. Devops & CICD: Recap
7. Guest speaker

![bg opacity](images/barcelonaLandscape.png)

---

- How can we scale our permissions when there are 100s of developers and environments?
  - Introduce IAM roles.
  - What is the difference with respect users?
  - Diagram where we see the "developer", "deployment" roles in 3 accounts.
  - How do we do it at Ohpen? Link IAM roles with AD users and groups.

---

- How do we control our services' permissions? -> With IAM roles!
  - Show get_user lambda and it's permissions.
  - Show save_user lambda and it's permissions.

---

- How can we link our code in Github to AWS ?
  - What we did last class but from Github.
  - Introduce Pull requests.
  - Introduce CICD.
  - Example: Create pull request in repository.
  - Example at Ohpen: (Ohpen-ionated) CICD pipeline.
    - Unit tests in CI
    - Integration tests in CD
    - E2E tests in CD

---

- How can we oversee costs in AWS?
  - Dashboards
  - Reports
  - Budgets
  - Types of costs:
    - Unblended
    - Amortized
    - Blended
    - Net Unblended
    - Net Amortized
  - Granularity of costs thanks to tags.

---
