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
| **langchain-ai/langchain** | ★ 132k | Fixed unbounded network hang in CI workflow — added HTTP timeout to `get_min_versions.py` so stuck requests no longer block the entire runner | [#35851](https://github.com/langchain-ai/langchain/pull/35851) ✅ |
| **run-llama/llama_index** | ★ 48k | Fixed mutable default argument in LanceDB managed index `__init__` — shared list across calls causing silent state leaks | [#20998](https://github.com/run-llama/llama_index/pull/20998) ✅ |
| **jeecgboot/JeecgBoot** | ★ 46k | Fixed `InputStream` resource leak in Tika document parser — moved allocation into try-with-resources so cleanup happens on every exit path | [#9548](https://github.com/jeecgboot/JeecgBoot/pull/9548) ✅ |
| **jxxghp/MoviePilot** | ★ 10k | Fixed indefinite worker hang in Alipan storage module — added HTTP request timeout to prevent network calls from blocking indefinitely | [#5574](https://github.com/jxxghp/MoviePilot/pull/5574) ✅ |
| **samuelclay/NewsBlur** | ★ 7.4k | Fixed mutable default argument in `canonical_string()` S3 utility — shared state across calls could corrupt request signing | [#2086](https://github.com/samuelclay/NewsBlur/pull/2086) ✅ |
| **FasterXML/jackson-databind** | ★ 3.7k | Fixed implicit platform encoding in JSON export — made `utf-8` explicit so output is consistent across environments | [#5829](https://github.com/FasterXML/jackson-databind/pull/5829) ✅ |
| **networknt/light-4j** | ★ 3.6k | Fixed `BufferedReader` resource leak in logging handler — moved allocation into try-with-resources so cleanup happens on every exit path | [#2728](https://github.com/networknt/light-4j/pull/2728) ✅ |
| **openrocket/openrocket** | ★ 2.6k | Fixed unclosed `BufferedWriter` in RASAero flight-data exporter — stream could leak on error exit path | [#3092](https://github.com/openrocket/openrocket/pull/3092) ✅ |
| **mll-lab-nu/RAGEN** | ★ 2.5k | Fixed mutable default argument in `load_config()` — shared list across calls causing silent state leaks in environment config | [#164](https://github.com/mll-lab-nu/RAGEN/pull/164) ✅ |

*...and [more](https://github.com/tejasae-afk?tab=overview) across apache/james-project, deephaven/deephaven-core, awslabs/amazon-neptune-tools, and others.*

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
