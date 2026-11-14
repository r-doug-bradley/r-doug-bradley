# Doug Bradley

I build document-processing agents for a procure-to-pay product, and I'm the company's AI lead at Fraxion. Twenty-six years of software, most of it C# and .NET on Azure, and since 2023 most of it AI in accounts payable. Phoenix, remote.

## What I've shipped

- **Invoice extraction with a correction loop.** A reviewer's corrections feed back as per-supplier examples, so the next invoice from that supplier comes in closer. About 60% of invoices at customers using AP automation arrive through extraction, over 99% at the heaviest users.
- **Invoice-line to PO-line matching** with a confidence score on every pair.
- **Advisor**, a rules engine with an AI anomaly signal and a gated explanation layer. It grades an invoice for review and says why.
- **An AP usage dashboard and a redesigned invoice work center**, so the people reviewing invoices see what the models did and what they changed.

How I work. The model proposes, the code disposes. Every fact that can be computed is computed before a model sees it. Every prompt change runs against a case set, three times, before it ships.

## In this account

- [claude-worklog](https://github.com/r-doug-bradley/claude-worklog). A Claude Code hook and skill that log session decisions and shipped work to a daily Markdown file, then draft a Friday update.
- [identity-platform](https://github.com/r-doug-bradley/identity-platform). Keystone, a working Duende IdentityServer on .NET 10 with the three kinds of client you meet in practice, a BFF, and a deploy that refuses to ship a password.

## Writing

- [rdougbradley.com](https://rdougbradley.com), where the posts live.
- [LinkedIn](https://www.linkedin.com/in/r-douglas-bradley), the *Setting Up Claude* series and what comes after it.

## Stack

C# and .NET, Azure Functions and SQL Server, Azure OpenAI and Azure Document Intelligence, Langfuse for traces and dataset runs, Claude Code for the building.
