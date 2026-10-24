# Jonathan L. Stoff

Orlando, FL ❖ [LinkedIn](https://www.linkedin.com/in/jonathanlstoff) ❖ [GitHub](https://github.com/JonathanLStoff) ❖ **[Download resume (PDF)](Resume.pdf)**

## Work Experience

### ARETUM (Library of Congress) — Washington, DC

**Technical Lead Full Stack/Infrastructure Architect** · *Aug. 2024 – Present*

- Ran and maintained team of 10 engineers across 3 time zones in an agile environment.
- Configured and deployed Kubernetes clusters using Terraform and gitlab-ci pipelines.
- Developed react apps for Folio systems by implementing the Stripes UI framework.
- Created pipelines and micro services that perform ETL functions in Python for library systems.
- Planned, designed, and program AWS infrastructure to complete my team’s goals.
- Made Lambdas and ECS tasks to integrate data across many departments internally and externally, using Restful APIs and AWS infrastructure. Added required infrastructure for these tasks including:
  - S3 Buckets, IAM Roles, Policies, and Users, Secrets, VPC, Subnets, Security groups, Firewall Manager, EC2, Elastic Container Service, Transfer Family (SFTP), RDS (Postgresql), Cloudwatch logging, KMS, ALB.
- Refactored code base to meet Agile deadlines and exceed client expectations.
- Designed and supported Infrastructure development using CI/CD pipelines and creating workflows that demonstrated the effectiveness of the needed architecture.

**Senior Python Developer** · *Aug. 2023 – Aug 2024*

- Coded Terraform and CI pipelines for new and existing projects.
  - Helped devops with TF issues other teams faced
  - Orchestrated AWS permission management and deployment pipelines using Terraform, ensuring seamless deployment across multiple environments; reduced deployment times by 40% and increased resource utilization efficiency by 25%
- Lead Company wide standups and ran demos for Product Owners.
  - Participated in Scrums in an AGILE workplace.
  - Lead grooming and development meetings.
- Mentored Other Employees on best coding practices and helped them to get up to date on the companies’ policies and latest Scrum and Agile methods.
- Assisted Devops to sustain image upgrades and instructing/coding SSL compliance.
- Updated Lambda and and other Python services with new Dockerfiles, Tests, build files, and custom libraries.
- Developed RESTful tests using Postman for Flask and Django frameworks.
- Implementation of new models and SQL queries for AWS RDS using PostgreSQL and Django.
- Was handpicked to join a company wide team that competed in the VA AI tech sprint challenge, and implemented AWS services that were vital to the challenge’s completion.

### Jerry Defalco Advertising — Maitland, FL

**Automation & Full-stack Developer** · *Mar. 2021 – July 2023*

- Managed automation DevOps for all employees using Python, Bash, Docker, and PyTest.
- Collaborated with other staff to identify and resolve issues using AWS for development in different environments.
- Architected and coded multiple sites for monitoring clusters and displaying information with Django, ChartJS & PostgreSQL.
- Created Python automations for Mac, Windows & Linux, on ARM & x86, to increase efficiency in file handling & Development.
  - Trained & Implemented AI models for email summarization using PyTorch in Python.

### Oasis Church — Loxahatchee, FL

**Automation Engineer & Full-stack Developer** · *Aug. 2019 – Feb. 2022*

- Built their website using Django, and implemented live stream and video into the site.
- Programmed custom backend solutions for virtual services and constructed custom automation programs using Python, Django, and Bash.
  - Produced Shell and Python scripts for Automating starting and stopping services.
  - Built programs in Visual Basic .NET to control virtual services using Power BI.

### Palm Beach Atlantic University — West Palm Beach, FL

**Automation & Embedded Systems Engineer** · *Mar. 2019 – Mar 2021*

- Programmed all embedded systems in Cafeteria such as menu screens, networking, and audio/video equipment.
- Environments included: Python, C++, Flask, Node.js, Cypress, and PostgreSQL
- Deployed AWS EC2 for testing and finding edge case issues with automations and software.
- Engineered an ensemble NLP system leveraging PyTorch and Keras, utilizing extensive datasets for training; enabled accurate issue parsing for troubleshooting across 3,500+ employees and students, reducing resolution time by 40%.
  - This AI technology summarizes the issues that the IT team receives to help with efficiency giving percentage scores to the most likely issue.
  - It also creates estimated time of completion for each issue based on the most likely issue.
- Used Postman to test development of APIs for our embedded systems, some of which used OpenCL.
- Assisted in data visualization for large datasets using Spark.
- Fabricated dashboards for showing approximate wait times for issue management and technical assistance; provided 10% higher ratings for technical support team.

### The Sharon Performing Arts Center — Lady Lake, FL

**Data Analyst Intern** · *June 2018 – Mar 2019*

- Developed strategies for streamlining development processes using GitHub.
- Developed new methods for unit tests using PyTest in AWS.
- Created apps for visualizing big datasets using Power BI, Tableau, & Python.
- Organized and compiled datasets using JSON, XML, & MS SQL server for ETL.
- Conducted data analysis to identify trends and patterns in audience attendance, ticket sales, and event popularity
- Participated in team meetings and presented findings to stakeholders, contributing to data-driven decision-making across departments.

### AMC Theaters — Leesburg, FL

**Embedded Systems Engineer Intern** · *Aug. 2016 – June 2018*

- Worked on practical applications for POS development in C++.
- Made automations to help with administrative tasks and emails.
- Developed pipelines to update databases with movie dates and times with SQL & Python.
- Assisted in programming and debugging microcontrollers and firmware to enhance the functionality of electronic devices used in theaters.
- Worked with cross-functional teams to identify opportunities for process improvement.

## Projects

- **[CuProphet](https://github.com/JonathanLStoff/CuProphet)** (C++, CUDA, Python; [on PyPI](https://pypi.org/project/cuprophet/)): GPU-accelerated build of Meta's Prophet forecasting library, with custom CUDA kernels wired into its Stan backend, plus OpenCL and multithreaded execution added to [CmdStanPy](https://github.com/JonathanLStoff/cmdstanpy_openCL_threaded).
- **[atome](https://github.com/JonathanLStoff/atome), [vtome](https://github.com/JonathanLStoff/vtome), [pfac](https://github.com/JonathanLStoff/pfac)** (Rust; on [crates.io](https://crates.io/users/JonathanLStoff)): a real-time audio engine with an allocation-free callback, lock-free ring buffer, multi-device routing and VST3/AU plugin hosting; a wgpu video engine that corner-pins frames with a per-pixel homography for keystone-corrected projection; and a streaming zip bundler with AES-256 encryption.
- **[Dystortion](https://github.com/JonathanLStoff/Dystortion)** (C++): distortion audio plugin released in AAX, VST3 and AU formats for macOS and Windows.
- **Home-lab monitoring** (Python, Docker, MQTT, WireGuard): [Home Assistant integration](https://github.com/JonathanLStoff/ha-device-status) (HACS) that checks devices by ping, port or MQTT on cron schedules and manages WireGuard through Linux netlink; Dockerized services for [MQTT health reporting](https://github.com/JonathanLStoff/py-heath-mqtt) and [tunnelled NVR backups](https://github.com/JonathanLStoff/wg-frigate-back) to SFTP/FTP/SMB.
- **Embedded and RF tools** (C, Rust, ESP32): Flipper Zero apps for multi-radio [signal tracking](https://github.com/JonathanLStoff/flipper_hot_cold) and [BLE GATT capture/replay](https://github.com/JonathanLStoff/flipper_shark_tooth); [SharkOS](https://github.com/JonathanLStoff/SharkOS), an Android (Tauri, Rust JNI) and ESP32 toolkit for BLE/Wi-Fi scanning, packet capture, IR and NFC.

## Education

**Palm Beach Atlantic University** — West Palm Beach, FL
*BA, Computer Information Technology*

## Certifications

Google IT Automation with Python | AWS Architect | Meta Back-End Developer Certified

## Skills

Python; GitLab; Object Oriented Programming; Terraform; API Development; Multithreading; Pipelines; Django; FastAPI; ASGI; AWS; CI/CD Automation; AI; RESTful; Github; CUDA; OpenCL; HTML, CSS, JavaScript; SQL & Databases; C++; Assembly x86; Visual Basic; Visual Studio; Cmake; XCode; Pandas; React & Angular; .NET; Excel; Rust; C; wgpu & GPU shaders; Real-time audio & DSP; VST3/AU/AAX plugins; Lock-free concurrency; ESP32 & Arduino firmware; Bluetooth LE (GATT); Sub-GHz RF; MQTT; Home Assistant; WireGuard & Linux networking; Tauri; Android (JNI); Docker; Bayesian forecasting (Prophet, Stan); PyPI & crates.io publishing
