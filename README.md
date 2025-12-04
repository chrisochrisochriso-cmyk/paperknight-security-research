🛡️ Paperknight Security Research — TIDS Scanner & Threat Data

TIDS — Threat Intelligence Data Scanner v3.0
Attack Surface + RCE + SSH + ML-Ready Telemetry More MODs coming soon. 

🚀 Overview

TIDS is an ultra-fast, non-disruptive domain scanner built for large-scale threat intelligence collection. It is designed to provide ML-ready telemetry and actionable security insights without exploiting live systems.

Speed & Scale: 11k domains scanned in ~86 seconds

Binary Size: 140 KB compiled C++ (lightweight & portable)

Low False Positives: <2%

Safe: Fully passive scanning, no live exploits executed

Capabilities:

Subdomain takeover detection

RCE detection (timing anomalies)

SSH exposure checks

Telemetry ready for AI ingestion

Output: JSONL containing all scan metadata for analysis or AI ingestion. No code is distributed, and no exploits are performed.

📊 Sample Top Domains

We provide hashed & salted samples to show the quality of our data. Each sample below represents 10 top domains from previous scans.

Shopify (Top 10)

{"ts":"2025-12-02T13:19:37Z","type":"scan_result","domain":"ada8bfbd0863f7ba928636350e3cbc5b","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":0,"https_time_ms":2271,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:37Z","type":"scan_result","domain":"425b3098d0f93d14897ab056e98911f6","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":1,"https_time_ms":2319,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:37Z","type":"scan_result","domain":"78862fbee376d2769c2bd5adfc6688fd","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":2507,"https_time_ms":42,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:37Z","type":"scan_result","domain":"187b561c8e09d51c757c44657b8cfb90","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":2513,"https_time_ms":36,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"487006379a81826d96790e2ca274359d","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":33,"https_time_ms":2681,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"a26515e8e88503bdbd24c9b57b61bfed","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":27,"https_time_ms":2558,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"3de6ebad5c516c5ea2430ba5c47f5734","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":415,"http_time_ms":31,"https_time_ms":491,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"04377d5db043f27451326b52d8192e8f","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":239,"https_time_ms":2686,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"0dd05c35cdd9482cc2a002fd5c5a4ea2","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":406,"https_time_ms":2457,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"8f0fea4b2c5f4987f2179a090e4ed3bf","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":498,"https_time_ms":2522,"ssh_time_ms":0}
{"ts":"2025-12-02T13:19:38Z","type":"scan_result","domain":"c116211481c998b1e72d9550e92582e2","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":1155,"http_time_ms":407,"https_time_ms":464,"ssh_time_ms":0}

Chime (Top 10)
{"ts":"2025-12-02T12:30:55Z","type":"scan_result","domain":"c4a0d4b59d131a5151106d01b047c80c","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":0,"https_time_ms":0,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:55Z","type":"scan_result","domain":"a5142560e13b9169beb2981ed9a0bfbe","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":0,"https_time_ms":0,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:55Z","type":"scan_result","domain":"5263bad402f72e59adf562f85f7a0ef4","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":0,"https_time_ms":0,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:55Z","type":"scan_result","domain":"47fd66e9bb660db4deb3ed4bf8feae45","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":7,"https_time_ms":0,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:56Z","type":"scan_result","domain":"39bea9d7e26dee62316fdeb0037b019f","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":689,"https_time_ms":0,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:56Z","type":"scan_result","domain":"3755f5fbb9b8fddf5fbd4f85fcdc9ff1","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":870,"https_time_ms":4,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:56Z","type":"scan_result","domain":"d7565b79f4dbe16bbade186ff4d6e0b3","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":218,"https_time_ms":740,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:56Z","type":"scan_result","domain":"bc2c0d2c413e9c6c86d1a5d1cd0bcae4","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":1092,"https_time_ms":119,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:56Z","type":"scan_result","domain":"08f7a8f7ddb890238c3e0f0337254269","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":1197,"https_time_ms":0,"ssh_time_ms":0}
{"ts":"2025-12-02T12:30:56Z","type":"scan_result","domain":"1a8780344b52c6a9e6af4b4555cd372b","takeover":true,"rce":false,"ssh_exposed":false,"confidence":1,"dns_time_ms":0,"http_time_ms":1124,"https_time_ms":30,"ssh_time_ms":0}

Coinbase (Top 10)
{"ts":"2025-12-02T14:52:10Z","type":"scan_result","domain":"08461eacbe236a1408fdce8bca9cfeaa","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":2769,"http_time_ms":3,"https_time_ms":52,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:10Z","type":"scan_result","domain":"3803a3145293719a7379f3a5580887c8","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":3272,"http_time_ms":2,"https_time_ms":41,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:10Z","type":"scan_result","domain":"ccacaacd654d1c3ea0f370c6b15fdb8e","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":3562,"http_time_ms":1,"https_time_ms":38,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:10Z","type":"ssh_detection","domain":"74be1691fac988ad31e618f62edf6c88","ip":"5ffdf735bc0b84f8","port":22,"banner":"SSH-2.0-AWS_SFTP_1.2","cves":[]}
{"ts":"2025-12-02T14:52:10Z","type":"scan_result","domain":"74be1691fac988ad31e618f62edf6c88","takeover":false,"rce":false,"ssh_exposed":true,"confidence":0,"dns_time_ms":2572,"http_time_ms":0,"https_time_ms":0,"ssh_time_ms":223}
{"ts":"2025-12-02T14:52:11Z","type":"scan_result","domain":"cc024da1f594cc49d998fef4574a3d25","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":3384,"http_time_ms":2,"https_time_ms":23,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:11Z","type":"scan_result","domain":"4b6b3515c6f8ba2c921d09de07d2e702","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":3620,"http_time_ms":1,"https_time_ms":17,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:11Z","type":"scan_result","domain":"335cfa6b70d0be306c074206d76696a0","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":5000,"https_time_ms":20,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:11Z","type":"scan_result","domain":"07eb8d240192865633f25e62cd00e92a","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":5000,"https_time_ms":42,"ssh_time_ms":0}
{"ts":"2025-12-02T14:52:11Z","type":"scan_result","domain":"87257656e3e0004adb12959404194823","takeover":false,"rce":false,"ssh_exposed":false,"confidence":0,"dns_time_ms":0,"http_time_ms":5005,"https_time_ms":26,"ssh_time_ms":0}

Note: Only 10 samples per dataset are shown. Full datasets are available under retainer agreement and  free scanner/ live demo 6 spaces left next week.  just contact my signal link,  (https://signal.me/#eu/rYqQmxPpIyI_DH2SMUPdXkyRF1g3GDRE00gDwPm3C7OTzHLb-UpBZJaYPGZ-fHiu)

💰 Data Offering !!

TIDS generates high-fidelity threat telemetry that is ready to feed AI pipelines and enterprise dashboards.

🌐 Web App / Browser Access — Coming Soon
A browser-based version of TIDS is under development. Soon, users will be able to:

Run limited free scans (up to 5 per account)

Receive ML-ready scan reports directly

Explore sanitized threat telemetry without installing anything

All scans are fully passive, and Paperknight retains rights to the raw telemetry. Early access and sample datasets are available for partners and early testers.

💰 Engagement Opportunities:

Data LLM Retainer contracts. 

Per-Scan Threat Reports.

Scan Threat Reports Retainer:  monthly/ weekly/ daily scans  

Contact Infomation: 

signal: https://signal.me/#eu/rYqQmxPpIyI_DH2SMUPdXkyRF1g3GDRE00gDwPm3C7OTzHLb-UpBZJaYPGZ-fHiu

Free scanner/ live demo 6 spaces left next week.  just contact me on my signal link.

Terms & Conditions:

All outputs are hashed and salted for privacy

Only Paperknight retains rights to raw scan telemetry

Clients receive aggregated & sanitized ML-ready data

Non-disruptive scanning, no exploits performed

🔒 Why Paperknight Data?

Real, validated intelligence from top enterprise infrastructure

Ultra-fast, passive scanning at scale

Extremely low false positives (<2%)

RCE, SSH, and takeover detection included

Directly ingestible into AI pipelines for modeling & analytics

Contact: Signal interest via email or GitHub DM for full dataset samples or engagement terms.

No personal data included.

Only public, legally scannable infrastructure is analyzed, all hashed and salted. 

Data is provided hashed and redacted to comply with privacy and security regulations.
