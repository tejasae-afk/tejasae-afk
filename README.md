<h1 align="center">Hey, I'm Tejas <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"></h1>

<p align="center">
  <a href="https://www.linkedin.com/in/tejasae/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=tejasae-afk&style=flat-square&color=blue" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Open%20Source-Contributor-06D6A0?style=flat-square&logo=github&logoColor=black" />
</p>

<p align="center">
  <strong>Software Engineer · Cloud Architect · MS CE @ NYU</strong><br/>
  I build scalable backend systems, cloud-native infrastructure, and secure distributed services.
</p>

---

### 🧑‍💻 About Me

- 🎓 **MS in Computer Engineering** @ New York University *(2024–2026)*
- 🏢 Former **DevOps Engineer** @ ProAzure Software Solutions — built serverless microservices & event-driven pipelines on AWS
- 🔐 Built a **confidential ML inference service** using AWS Nitro Enclaves with attestation-gated key release
- 🧪 Researching **LLM-driven hardware code generation** under Dr. Ramesh Karri (ECE Chair, NYU)

---

### 🛠️ Tech Stack

| Domain | Technologies |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Cloud** | ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Infrastructure** | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) |
| **Backend & Data** | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) |
| **Security** | IAM · KMS · Nitro Enclaves · Cognito · Secrets Manager · JWT · Service Accounts |

---

### 📜 Certifications

<p>
  <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Professional-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" > <img src="https://img.shields.io/badge/AWS-Security_Specialty-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" ><br/>
  <img src="https://img.shields.io/badge/GCP-Professional_Cloud_Architect-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" >
  <img src="https://img.shields.io/badge/Azure-Developer_Associate-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" >
</p>

---

### 🔥 Featured Projects

| Project | Stack | Description |
|---|---|---|
| [**Confidential ML Feature Store**](https://github.com/tejasae-afk/confidential-ml-feature-store) | Python · FastAPI · Nitro Enclaves · KMS · DynamoDB | Hardware-isolated multi-tenant inference with attestation-gated key release and vsock RPC. Secrets never leave the enclave. |
| [**Multi-Cloud Kubernetes Platform**](https://github.com/tejasae-afk/Multi-Cloud-Kubernetes-Platform-AKS-GKE) | Kubernetes · GKE · AKS · Terraform · Helm | Production-grade platform spanning GCP and Azure — unified ingress, autoscaling, RBAC, and GitOps-ready manifests. |

---

### 🤝 Open Source Contributions

Merged patches in production codebases used by thousands of developers:

| Repository | Stars | Contribution | PR |
|---|---|---|---|
| **langchain-ai/langchain** | ★ 132k | Eliminated a silent CI deadlock — unguarded HTTP calls in `get_min_versions.py` could stall the entire GitHub Actions runner indefinitely; added a request timeout to bound worst-case latency | [#35851](https://github.com/langchain-ai/langchain/pull/35851) ✅ |
| **run-llama/llama_index** | ★ 48k | Patched a subtle data-corruption hazard in the LanceDB managed index — mutable default argument in `__init__` caused list state to bleed across unrelated instances | [#20998](https://github.com/run-llama/llama_index/pull/20998) ✅ |
| **jeecgboot/JeecgBoot** | ★ 46k | Closed a file-descriptor leak in the Tika document parser — `InputStream` was allocated before the `try` block, leaving it open on any exception path; moved into try-with-resources | [#9548](https://github.com/jeecgboot/JeecgBoot/pull/9548) ✅ |
| **jxxghp/MoviePilot** | ★ 10k | Fixed a worker thread that could hang forever — Alipan storage module made unbounded HTTP calls with no timeout, freezing the thread pool under slow or unreachable endpoints | [#5574](https://github.com/jxxghp/MoviePilot/pull/5574) ✅ |
| **samuelclay/NewsBlur** | ★ 7.4k | Fixed a mutable default argument in the S3 `canonical_string()` signing utility — shared list state across calls risked silently corrupting AWS request signatures | [#2086](https://github.com/samuelclay/NewsBlur/pull/2086) ✅ |
| **FasterXML/jackson-databind** | ★ 3.7k | Hardened JSON export against platform encoding drift — implicit charset in `export_to_json` produced garbled output on non-UTF-8 JVMs; made UTF-8 explicit | [#5829](https://github.com/FasterXML/jackson-databind/pull/5829) ✅ |
| **networknt/light-4j** | ★ 3.6k | Sealed a `BufferedReader` leak in the logging handler — resource was opened outside try-with-resources so any exception on the read path left the descriptor open | [#2728](https://github.com/networknt/light-4j/pull/2728) ✅ |
| **openrocket/openrocket** | ★ 2.6k | Fixed `BufferedWriter` leak in the RASAero flight-data exporter — stream was never closed on error exit paths, risking data truncation and fd exhaustion in long sessions | [#3092](https://github.com/openrocket/openrocket/pull/3092) ✅ |
| **mll-lab-nu/RAGEN** | ★ 2.5k | Fixed mutable default in `load_config()` — shared list persisted across invocations, causing environment configs to accumulate entries silently across RL training runs | [#164](https://github.com/mll-lab-nu/RAGEN/pull/164) ✅ |

*...and [more](https://github.com/tejasae-afk?tab=overview) across apache/james-project, deephaven/deephaven-core, awslabs/amazon-neptune-tools, and others.*

---

#### Option A — compact table with expandable details

| Repository | Stars | PR |
|---|---:|---|
| <details><summary><b>langchain-ai/langchain</b></summary>Eliminated a silent CI deadlock — unguarded HTTP calls could stall the entire GitHub Actions runner indefinitely</details> | ★ 132k | [#35851](https://github.com/langchain-ai/langchain/pull/35851) ✅ |
| <details><summary><b>run-llama/llama_index</b></summary>Patched a data-corruption hazard — mutable default in `__init__` caused list state to bleed across unrelated instances</details> | ★ 48k | [#20998](https://github.com/run-llama/llama_index/pull/20998) ✅ |
| <details><summary><b>jeecgboot/JeecgBoot</b></summary>Closed a file-descriptor leak in the Tika document parser — `InputStream` left open on any exception path</details> | ★ 46k | [#9548](https://github.com/jeecgboot/JeecgBoot/pull/9548) ✅ |
| <details><summary><b>jxxghp/MoviePilot</b></summary>Fixed a worker thread that could hang forever — unbounded HTTP calls with no timeout froze the thread pool</details> | ★ 10k | [#5574](https://github.com/jxxghp/MoviePilot/pull/5574) ✅ |
| <details><summary><b>samuelclay/NewsBlur</b></summary>Fixed mutable default in S3 signing utility — shared state across calls could silently corrupt AWS request signatures</details> | ★ 7.4k | [#2086](https://github.com/samuelclay/NewsBlur/pull/2086) ✅ |
| <details><summary><b>FasterXML/jackson-databind</b></summary>Hardened JSON export against platform encoding drift — implicit charset produced garbled output on non-UTF-8 JVMs</details> | ★ 3.7k | [#5829](https://github.com/FasterXML/jackson-databind/pull/5829) ✅ |
| <details><summary><b>networknt/light-4j</b></summary>Sealed a `BufferedReader` leak — resource opened outside try-with-resources left fd open on any exception</details> | ★ 3.6k | [#2728](https://github.com/networknt/light-4j/pull/2728) ✅ |
| <details><summary><b>openrocket/openrocket</b></summary>Fixed `BufferedWriter` leak in RASAero exporter — stream never closed on error paths, risking data truncation</details> | ★ 2.6k | [#3092](https://github.com/openrocket/openrocket/pull/3092) ✅ |
| <details><summary><b>mll-lab-nu/RAGEN</b></summary>Fixed mutable default in `load_config()` — shared list accumulated entries silently across RL training runs</details> | ★ 2.5k | [#164](https://github.com/mll-lab-nu/RAGEN/pull/164) ✅ |

---

#### Option B — compact one-liner table

| Repository | Stars | Fix | PR |
|---|---:|---|---|
| **langchain-ai/langchain** | ★ 132k | CI deadlock: bounded unbounded HTTP calls in runner workflow | [#35851](https://github.com/langchain-ai/langchain/pull/35851) ✅ |
| **run-llama/llama_index** | ★ 48k | Data corruption: fixed mutable default in LanceDB index `__init__` | [#20998](https://github.com/run-llama/llama_index/pull/20998) ✅ |
| **jeecgboot/JeecgBoot** | ★ 46k | Resource leak: closed `InputStream` on all paths in Tika parser | [#9548](https://github.com/jeecgboot/JeecgBoot/pull/9548) ✅ |
| **jxxghp/MoviePilot** | ★ 10k | Thread hang: added timeout to Alipan HTTP calls | [#5574](https://github.com/jxxghp/MoviePilot/pull/5574) ✅ |
| **samuelclay/NewsBlur** | ★ 7.4k | Silent corruption: fixed mutable default in S3 signing utility | [#2086](https://github.com/samuelclay/NewsBlur/pull/2086) ✅ |
| **FasterXML/jackson-databind** | ★ 3.7k | Encoding drift: hardened JSON export with explicit UTF-8 | [#5829](https://github.com/FasterXML/jackson-databind/pull/5829) ✅ |
| **networknt/light-4j** | ★ 3.6k | Resource leak: sealed `BufferedReader` in try-with-resources | [#2728](https://github.com/networknt/light-4j/pull/2728) ✅ |
| **openrocket/openrocket** | ★ 2.6k | Resource leak: closed `BufferedWriter` on all exit paths | [#3092](https://github.com/openrocket/openrocket/pull/3092) ✅ |
| **mll-lab-nu/RAGEN** | ★ 2.5k | Silent state bleed: fixed mutable default in `load_config()` | [#164](https://github.com/mll-lab-nu/RAGEN/pull/164) ✅ |

---

#### Option C — bulleted list

Merged patches across **18 production codebases** (★ 330k+ combined):

- 🔒 **[langchain-ai/langchain](https://github.com/langchain-ai/langchain/pull/35851)** ★132k — eliminated CI deadlock from unbounded HTTP calls in runner workflow
- 🔒 **[run-llama/llama_index](https://github.com/run-llama/llama_index/pull/20998)** ★48k — patched data-corruption hazard from mutable default in LanceDB index
- 🔒 **[jeecgboot/JeecgBoot](https://github.com/jeecgboot/JeecgBoot/pull/9548)** ★46k — closed `InputStream` leak in Tika document parser
- 🔒 **[jxxghp/MoviePilot](https://github.com/jxxghp/MoviePilot/pull/5574)** ★10k — fixed thread hang from unbounded Alipan HTTP calls
- 🔒 **[samuelclay/NewsBlur](https://github.com/samuelclay/NewsBlur/pull/2086)** ★7.4k — fixed mutable default corrupting S3 request signatures
- 🔒 **[FasterXML/jackson-databind](https://github.com/FasterXML/jackson-databind/pull/5829)** ★3.7k — hardened JSON export against platform encoding drift
- 🔒 **[networknt/light-4j](https://github.com/networknt/light-4j/pull/2728)** ★3.6k — sealed `BufferedReader` fd leak in logging handler
- 🔒 **[openrocket/openrocket](https://github.com/openrocket/openrocket/pull/3092)** ★2.6k — closed `BufferedWriter` leak in RASAero flight-data exporter
- 🔒 **[mll-lab-nu/RAGEN](https://github.com/mll-lab-nu/RAGEN/pull/164)** ★2.5k — fixed config state bleed across RL training runs

---

### 📊 GitHub Stats

<div align="center">

<table style="border-collapse: collapse;">
<tr>
<td align="center" style="padding: 8px;">

<img src="https://github-readme-stats.vercel.app/api?username=tejasae-afk&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" width="380" />

</td>
<td align="center" style="padding: 8px;">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tejasae-afk&layout=compact&theme=tokyonight&hide_border=true" width="290" />

</td>
</tr>
</table>

<br/>

<table style="border-collapse: collapse;">
<tr>

<td align="center" style="padding: 8px;">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=tejasae-afk&theme=dark&hide_border=true" height="170"/>
</td>

<td align="center" style="padding: 8px;">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=tejasae-afk&theme=react-dark&hide_border=true&area=true" width="450" />
</td>

</tr>
</table>

</div>

---
