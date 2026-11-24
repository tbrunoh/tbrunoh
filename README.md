<div align="center">

<img src="./banner.svg" alt="Tom Bruno. Product and Ecosystem Leader, AI Ecosystems. Founder, Korext. Building ACE." width="100%">

<br><br>

<a href="https://korext.com"><img src="https://img.shields.io/badge/Korext-Platform-1E40AF?style=flat-square&labelColor=0B1838" alt="Korext Platform"></a>
<a href="https://oss.korext.com"><img src="https://img.shields.io/badge/Korext-Open%20Standards-06B6D4?style=flat-square&labelColor=0B1838" alt="Korext Open Standards"></a>
<a href="#ace-the-african-context-engine"><img src="https://img.shields.io/badge/ACE-African%20Context%20Engine-0E7490?style=flat-square&labelColor=0B1838" alt="ACE"></a>
<a href="https://github.com/korext"><img src="https://img.shields.io/github/stars/korext?style=flat-square&color=3B82F6&labelColor=0B1838&label=Org%20Stars" alt="Korext org stars"></a>
<a href="https://linkedin.com/in/tbrunoh"><img src="https://img.shields.io/badge/LinkedIn-tbrunoh-0A66C2?style=flat-square&labelColor=0B1838&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

<br><br>

<sub><b>AI ECOSYSTEMS</b> &nbsp;·&nbsp; <b>CONTEXT FOR AFRICA</b> &nbsp;·&nbsp; <b>OPEN STANDARDS</b></sub>

<sub><a href="#about">About</a> &nbsp;·&nbsp; <a href="#ace-the-african-context-engine">ACE</a> &nbsp;·&nbsp; <a href="#inclusive-skin-ai">Skin AI</a> &nbsp;·&nbsp; <a href="#korext-the-stack">Korext</a> &nbsp;·&nbsp; <a href="#journey">Journey</a> &nbsp;·&nbsp; <a href="#connect">Connect</a></sub>

</div>

<br>

## About

I work where AI systems meet the ecosystems around them: the agents, platforms, publishers and developers that have to trust one another for any of it to work.

By day I am a Product and Ecosystem Leader in AI Ecosystems. Outside of it I am building **[ACE](#ace-the-african-context-engine)**, an open context engine that grounds AI in hyperlocal African knowledge, and **[Korext](https://korext.com)**, a governance runtime for AI generated code with **[seven open standards](https://oss.korext.com)** that make AI written software traceable, licensable and accountable.

<br>

<table>
<tr>
<td width="50%" valign="top">

<sub>01 &nbsp; DAY JOB</sub>

### AI Ecosystems

How agents, platforms and publishers connect: access, identity, incentives and the protocols that hold them together.

</td>
<td width="50%" valign="top">

<sub>02 &nbsp; BUILDING</sub>

### ACE, the African Context Engine

One open context engine behind every entry point people already use: voice, USSD, SMS, WhatsApp, agents, radio and MCP.

<sub>Pre-alpha. Repository opening soon.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<sub>03 &nbsp; OPEN SOURCE</sub>

### Korext Standards

Seven open standards for AI code provenance. CC0 specifications, Apache 2.0 code, CC BY 4.0 data.

<a href="https://oss.korext.com"><b>oss.korext.com →</b></a>

</td>
<td width="50%" valign="top">

<sub>04 &nbsp; COMPANY</sub>

### Korext Platform

The runtime that enforces those standards for regulated industries, with a signed proof bundle for every scan.

<a href="https://korext.com"><b>korext.com →</b></a>

</td>
</tr>
</table>

<br>

## ACE: the African Context Engine

Global models do not know which pest control works at 2,100m in the Rift Valley, what tomatoes cost on Thursdays at Wakulima, or how land law changes 30km across a border. ACE encodes that hyperlocal knowledge once and serves it through every channel, on any phone, with a safety rail that hands urgent cases to a human.

<div align="center">
<img src="./ace.svg" alt="ACE architecture: eight entry points, one identity, an engine that runs safety, intent, context and cited answers, over context packs and mobile money" width="100%">
</div>

<sub>Open core: the engine is free; verified, expert reviewed context carries commercial terms. Pre-alpha. Repository opening soon.</sub>

<br><br>

## Inclusive Skin AI

Most skin analysis models are trained on lighter skin, so they misread darker tones and give advice that does not fit. This project starts from the other end: an end to end system built for melanin-rich skin first, from photo capture and labeling to trained models and a personalized skincare assistant.

<div align="center">
<img src="./skin.svg" alt="Inclusive skin AI pipeline: capture, label, train, serve and advise, with skin tone measured on the Monk Skin Tone scale" width="100%">
</div>

<table>
<thead>
<tr><th align="left">Layer</th><th align="left">Repository</th><th align="left">What it does</th></tr>
</thead>
<tbody>
<tr><td><sub>MODEL</sub></td><td><a href="https://github.com/tbrunoh/ml-ai-skintone"><b>ml-ai-skintone</b></a></td><td>Skin tone classifier on the Monk Skin Tone scale, with training and Vertex AI inference</td></tr>
<tr><td><sub>MODEL</sub></td><td><a href="https://github.com/tbrunoh/ml-ai-skin-conditions"><b>ml-ai-skin-conditions</b></a></td><td>Skin condition model package, early stage</td></tr>
<tr><td><sub>CORE</sub></td><td><a href="https://github.com/tbrunoh/ml-ai-core"><b>ml-ai-core</b></a></td><td>Shared Python library for models, utilities and image storage</td></tr>
<tr><td><sub>PRODUCT</sub></td><td><a href="https://github.com/tbrunoh/ml-ai-skintone-ui"><b>ml-ai-skintone-ui</b></a></td><td>Next.js app for skin tone analysis, deployed by CI/CD on every push</td></tr>
<tr><td><sub>RESEARCH</sub></td><td><a href="https://github.com/tbrunoh/ml-ai-samples"><b>ml-ai-samples</b></a></td><td>Reference experiments: class prediction, GANs and MNIST baselines</td></tr>
</tbody>
</table>

<sub>The upload API, labeling service, inference API and Terraform infrastructure stay private.</sub>

<br><br>

## Korext: The Stack

<div align="center">
<img src="./stack.svg" alt="The Korext stack: seven open standards, the Korext platform, and enforce-action in CI/CD" width="100%">
</div>

<br>

## Korext Open Standards

<table>
<thead>
<tr><th align="left">Role</th><th align="left">Standard</th><th align="left">What it does</th><th align="left">Release</th></tr>
</thead>
<tbody>
<tr>
<td><sub>TRACK</sub></td>
<td><a href="https://github.com/korext/ai-attestation"><b>ai-attestation</b></a></td>
<td>Verifiable provenance for the leading AI coding tools</td>
<td><a href="https://www.npmjs.com/package/@korext/ai-attestation"><img src="https://img.shields.io/npm/v/@korext/ai-attestation?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
<tr>
<td><sub>DECLARE</sub></td>
<td><a href="https://github.com/korext/ai-license"><b>ai-license</b></a></td>
<td>Licensing framework for AI generated code</td>
<td><a href="https://www.npmjs.com/package/@korext/ai-license"><img src="https://img.shields.io/npm/v/@korext/ai-license?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
<tr>
<td><sub>SCAN</sub></td>
<td><a href="https://github.com/korext/supply-chain-attestation"><b>supply-chain-attestation</b></a></td>
<td>AI provenance across SBOM and signature ecosystems</td>
<td><a href="https://www.npmjs.com/package/@korext/supply-check"><img src="https://img.shields.io/npm/v/@korext/supply-check?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
<tr>
<td><sub>REPORT</sub></td>
<td><a href="https://github.com/korext/ai-incident-registry"><b>ai-incident-registry</b></a></td>
<td>Public incident taxonomy and registry for AI code failures</td>
<td><a href="https://www.npmjs.com/package/@korext/incident-report"><img src="https://img.shields.io/npm/v/@korext/incident-report?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
<tr>
<td><sub>MEASURE</sub></td>
<td><a href="https://github.com/korext/ai-code-radar"><b>ai-code-radar</b></a></td>
<td>Detection pattern library and live adoption data for AI authored code</td>
<td><a href="https://www.npmjs.com/package/@korext/radar-data"><img src="https://img.shields.io/npm/v/@korext/radar-data?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
<tr>
<td><sub>DETECT</sub></td>
<td><a href="https://github.com/korext/ai-regression-database"><b>ai-regression-database</b></a></td>
<td>Regression fingerprinting for AI code patterns</td>
<td><a href="https://www.npmjs.com/package/@korext/regression-submit"><img src="https://img.shields.io/npm/v/@korext/regression-submit?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
<tr>
<td><sub>SUSTAIN</sub></td>
<td><a href="https://github.com/korext/commit-carbon"><b>commit-carbon</b></a></td>
<td>Emissions accounting for software changes</td>
<td><a href="https://www.npmjs.com/package/@korext/commit-carbon"><img src="https://img.shields.io/npm/v/@korext/commit-carbon?style=flat-square&color=1E40AF&labelColor=0B1838&label=npm" alt="npm version"></a></td>
</tr>
</tbody>
</table>

<sub>Specifications CC0 &nbsp;·&nbsp; Code Apache 2.0 &nbsp;·&nbsp; Data CC BY 4.0 &nbsp;·&nbsp; Built so anyone can adopt, extend and contribute back without legal friction.</sub>

<br><br>

## Journey

<div align="center">
<img src="./journey.svg" alt="Career from Google Kenya to AI Ecosystems, and education at TU Dublin, HEC Paris, UC Berkeley and George Washington University" width="100%">
</div>

<br>

Born and raised in Kenya. More than a decade at Google, including five years shaping product and platform strategy for Chrome, used by billions of people. I invest in technology led founders in frontier markets with Black Angel Group and advise Silicon Xchange, which connects Silicon Valley and Africa.

<br>

## Connect

<div align="center">

<a href="https://linkedin.com/in/tbrunoh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://korext.com"><img src="https://img.shields.io/badge/Korext_Platform-1E40AF?style=for-the-badge" alt="Korext Platform"></a>
<a href="https://oss.korext.com"><img src="https://img.shields.io/badge/Korext_Open_Source-06B6D4?style=for-the-badge" alt="Korext Open Source"></a>
<a href="mailto:maintainers@korext.com"><img src="https://img.shields.io/badge/Email-0B1838?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

</div>

<br>

---

<div align="center">
<sub><i>The next decade of software gets written faster than humans can review it. Infrastructure for accountability has to ship at the same pace as the agents producing the code.</i></sub>
</div>
