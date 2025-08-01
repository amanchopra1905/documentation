---
id: hyperexecute-shared-cloud-usage-limit
title: Daily Usage Limit Per Organization | HyperExecute
hide_title: false
sidebar_label: Daily Usage Limit Per Organization
description: LambdaTest enforces a daily test execution time limit at the organization level, based on the number of concurrent sessions, to ensure fair usage and system stability.
keywords:
  - over-exploitation
  - lambdatest best practices
  - automation testing
  - concurrency
  - parallel sessions
  - automation
image: /assets/images/og-images/default-user-image.png
url: https://www.lambdatest.com/support/docs/hyperexecute-shared-cloud-usage-limit/
site_name: LambdaTest
slug: hyperexecute-shared-cloud-usage-limit/
---

<script type="application/ld+json"
      dangerouslySetInnerHTML={{ __html: JSON.stringify({
       "@context": "https://schema.org",
        "@type": "BreadcrumbList",
        "itemListElement": [{
          "@type": "ListItem",
          "position": 1,
          "name": "Home",
          "item": "https://www.lambdatest.com"
        },{
          "@type": "ListItem",
          "position": 2,
          "name": "Support",
          "item": "https://www.lambdatest.com/support/docs/"
        },{
          "@type": "ListItem",
          "position": 3,
          "name": "Daily Usage Limit",
          "item": "https://www.lambdatest.com/support/docs/daily-usage-limit/"
        }]
      })
    }}
></script>
To ensure fair usage, maintain system stability, and promote optimal test practices across all our users, LambdaTest enforces a daily usage limit on test execution time at the organization level. Each organization is allocated a maximum allowable test duration per day, calculated based on the number of concurrent (parallel) sessions provisioned to the account. This safeguard helps prevent overutilization and ensures equitable access to resources across the platform.

## Why This Matters
Running long-duration test sessions—especially those exceeding 120 minutes—can cause memory and CPU spikes that impact system performance and reliability. To prevent such disruptions and improve the efficiency of test execution, we encourage users to:

- Split long-running tests into smaller, modular suites.
- Implement test retries, timeouts, and teardown routines to handle edge cases and resource leaks.
- Use parallelization effectively to optimize test execution time without extending the runtime of individual sessions.

By adhering to these guidelines, your team not only aligns with industry best practices but also ensures smoother and more reliable test runs on LambdaTest infrastructure.

## Daily Test Time Limits by Parallel Sessions
The daily usage cap scales linearly based on the number of parallel sessions available to your organization. Below is a reference table:

| PARALLEL SESSIONS | COMPLETED RUN TIME (HRS) |
| ---------- | ----------------- |
| 1 | 6 |
| 2 | 12 |
| 3 | 18 |
| 4 | 24 |
| 5 | 30 |
| 6 | 36 |
| 7 | 42 |
| 8 | 48 |
| 9 | 54 |
| 10 | 60 |
| 11 | 66 |
| 12 | 72 |
| 13 | 78 |
| 14 | 84 |
| 15 | 90 |
| 16 | 96 |
| 17 | 102 |
| 18 | 108 |
| 19 | 114 |
| 20 | 120 |
| 21 | 126 |
| 22 | 132 |
| 23 | 138 |
| 24 | 144 |
| 25 | 150 |
| 26 | 156 |
| 27 | 162 |
| 28 | 168 |
| 29 | 174 |
| 30 | 180 |
| 31 | 186 |
| 32 | 192 |
| 33 | 198 |
| 34 | 204 |
| 35 | 210 |
| 36 | 216 |
| 37 | 222 |
| 38 | 228 |
| 39 | 234 |
| 40 | 240 |
| 41 | 246 |
| 42 | 252 |
| 43 | 258 |
| 44 | 264 |
| 45 | 270 |
| 46 | 276 |
| 47 | 282 |
| 48 | 288 |
| 49 | 294 |
| 50 | 300 |
| 51 | 306 |
| 52 | 312 |
| 53 | 318 |
| 54 | 324 |
| 55 | 330 |
| 56 | 336 | 
| 57 | 342 |
| 58 | 348 |
| 59 | 354 |
| 60 | 360 |
| 61 | 366 |
| 62 | 372 |
| 63 | 378 |
| 64 | 384 |
| 65 | 390 |
| 66 | 396 |
| 67 | 402 |
| 68 | 408 |
| 69 | 414 |
| 70 | 420 |
| 71 | 426 |
| 72 | 432 |
| 73 | 438 |
| 74 | 444 |
| 75 | 450 |
| 76 | 456 |
| 77 | 462 |
| 78 | 468 |
| 79 | 474 |
| 80 | 480 |
| 81 | 486 |
| 82 | 492 |
| 83 | 498 |
| 84 | 504 |
| 85 | 510 |
| 86 | 516 |
| 87 | 522 |
| 88 | 528 |
| 89 | 534 |
| 90 | 540 |
| 91 | 546 |
| 92 | 552 |
| 93 | 558 |
| 94 | 564 |
| 95 | 570 |
| 96 | 576 |
| 97 | 582 |
| 98 | 588 |
| 99 | 594 |
| 100 | 600 |

> **Note :** If your test executions consistently exceed the recommended runtime or you face test instability, please consider reviewing your test strategy or reaching out to our support team for optimization guidance.