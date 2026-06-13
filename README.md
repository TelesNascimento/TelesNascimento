# Darlysson Teles

Senior Software Engineer at [The Access Group](https://www.theaccessgroup.com). Payments and
security on the JVM. (US / UK / EU / APAC).

Focus: PCI DSS compliance, payments integration, Quarkus / Jakarta EE, fault tolerance.

**Stack**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=flat&logo=quarkus&logoColor=white)
![MicroProfile](https://img.shields.io/badge/MicroProfile-004B6E?style=flat)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Security**

![PCI DSS](https://img.shields.io/badge/PCI%20DSS-SAQ%20D%20v4.0.1-blue?style=flat)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![AWS WAF](https://img.shields.io/badge/AWS%20WAF-FF9900?style=flat&logo=amazonaws&logoColor=white)

---

**Selected work**

Led a full PCI DSS SAQ D v4.0.1 implementation across 5 payment processors (Adyen, Stripe,
FreedomPay, WorldPay, Shift4), ~798K transactions. Built Subresource Integrity / CSP
enforcement (Req 6.4.3), a daily payment-page tamper-detection pipeline (Req 11.6.1, on
Azure DevOps + Datadog), and coordinated an external penetration test. Production on AWS ECS
Fargate, Lambda, WAF, CloudTrail, AppConfig.

---

**Open source**

- [`smallrye-fault-tolerance#1276`](https://github.com/smallrye/smallrye-fault-tolerance/pull/1276) (merged) -
  fix annotation lookup when fault-tolerance annotations come from a class-level stereotype.
- [`microprofile-ft-stereotype-portability`](https://github.com/TelesNascimento/microprofile-ft-stereotype-portability) -
  portability reproduction for stereotype-based fault tolerance.
- [`smallrye-ft-owb-interceptor-binding`](https://github.com/TelesNascimento/smallrye-ft-owb-interceptor-binding) -
  reproducer and analysis of an OpenWebBeans transitive interceptor-binding incompatibility (issue #711).
- [`quarkus-panache-audit`](https://github.com/TelesNascimento/quarkus-panache-audit) -
  `@CreatedBy` / `@LastModifiedBy` for Quarkus Panache (fills quarkusio #53104).
- [`quarkus-webhooks`](https://github.com/TelesNascimento/quarkus-webhooks) -
  multi-provider webhook signature verification for Quarkus.

In progress: proposing TCK / spec portability improvements for stereotype-based fault
tolerance across CDI implementations (SmallRye Fault Tolerance, OpenWebBeans), so the same
behavior holds regardless of the underlying CDI engine.

---

**Field notes**

- [`pci-dss-field-notes`](https://github.com/teles-forge/pci-dss-field-notes) -
  sanitized, vendor-neutral field notes for PCI DSS SAQ D v4.0.1: scope and inventory,
  service providers and AOCs, targeted risk analysis (12.3.1), QSA prep, and deep dives on
  payment-page script integrity (6.4.3 SRI/CSP) and tamper detection (11.6.1).

---

**Contact**

[LinkedIn](https://www.linkedin.com/in/dev-teles-nascimento/) ·
[teles-forge](https://github.com/teles-forge)
