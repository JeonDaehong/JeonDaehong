<img width="1500" height="600" alt="Image" src="https://github.com/user-attachments/assets/093baa11-0c84-42de-8189-f279bb553d1d" />

---

<p align="center" style="font-size: 28px; font-weight: bold;">
  <strong>Hello! I am Daehong Jeon, a software engineer and data engineer.</strong>
</p>

<div style="display: flex; justify-content: center; gap: 80px; align-items: center;">
  <div style="display: flex; flex-direction: column; align-items: center;">
    <a href="https://jeondaehong.github.io/">
      <img width="50" height="50" src="https://github.com/user-attachments/assets/f3e01811-c3dd-42fd-8927-92bcf59cbc03" alt="My Blog" />
    </a>
    <div style="margin-top: 8px; font-size: 14px; font-weight: bold;">My Blog</div>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center;">
    <a href="mailto:daehong770@gmail.com">
      <img width="50" height="50" src="https://github.com/user-attachments/assets/a1b40ffb-7ead-43f5-848b-2ec3a7f75cde" alt="My Email" />
    </a>
    <div style="margin-top: 8px; font-size: 14px; font-weight: bold;">My Email</div>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center;">
    <a href="https://www.linkedin.com/in/daehong-jeon">
      <img width="50" height="50" src="https://github.com/user-attachments/assets/18a2e315-2214-491b-b84b-2cc174327a7d" alt="My Linkedin" />
    </a>
    <div style="margin-top: 8px; font-size: 14px; font-weight: bold;">My Linkedin</div>
  </div>
</div>



## 🧑‍💻 About Me  
**💻 Spark & Iceberg-based Large-Scale Data Pipeline Engineer**  
- Extensive experience in the finance and e-commerce domains, covering everything from Hadoop to modern cloud platforms. Skilled in processing **tens to hundreds of terabytes** of data, developing Spark & cloud-based ETL pipelines, optimizing Hadoop legacy systems, and designing highly available, failover-ready, and concurrency-controlled data infrastructures.

**🌐 I love contributing to open source**  
- Active contributor and maintainer for data engineering projects such as **Apache Iceberg** and **Apache Kafka**, including issue triage, PR reviews, and documentation improvements.  
- **Open Source Mentoring (2025.05~)** — Engaged in fostering a healthy and sustainable open source culture in Korea.

**🎯 My Goals**  
- To grow as a **technology leader** who internalizes and spreads the latest trends within organizations,  
while designing and operating **scalable and reliable architectures** for large-scale, high-traffic environments.

---

<h2> 💡 Tech Stack </h2> 

<p>
  <img src="https://img.shields.io/badge/Iceberg-50ABF1?style=flat&logo=ApacheIaceberg&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=ApacheSpark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hadoop-A81C7D?style=flat&logo=ApacheHadoop&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hive-C2A633?style=flat&logo=ApacheHive&logoColor=white"/>
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=DuckDB&logoColor=black"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scala-DC322F?style=flat&logo=Scala&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat&logo=ApacheKafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=OpenJDK&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white"/> 
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=SpringBoot&logoColor=white"/> 
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/> 
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=NGINX&logoColor=white"/>  
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white"/> 
  <img src="https://img.shields.io/badge/NaverCloud-03C75A?style=flat&logo=Naver&logoColor=white"/> 
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=AmazonAWS&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=Linux&logoColor=white"/>
</p>

<br>

<h2> 🛠️ Open Source Contributions </h2> 

### [1. 🧊 Apache/Iceberg](https://github.com/apache/iceberg)<br/>
#### [1.1. PR: Iceberg Flink Catalog v2.0 Remove the MiniClusterWithClientResource dependency](https://github.com/apache/iceberg/pull/13021#issuecomment-2903837698)
- **Fix:** Removed the unnecessary *JUnit 4* test dependency `MiniClusterWithClientResource` and migrated the Flink catalog tests in Apache Iceberg to be compatible with *JUnit 5*. This change simplifies the test setup for Iceberg’s Flink catalog module, reduces test complexity, improves maintainability, and aligns with both *Flink 2.0* and modern testing practices.
- → **Main Branch Merge Date: May 23, 2025**
#### [1.2. PR: Backporting Removal of MiniClusterWithClientResource from Iceberg Flink Catalog v1.19, v1.20](https://github.com/apache/iceberg/pull/13165)
- **Fix:** Backported the removal of the MiniClusterWithClientResource dependency and the migration to JUnit 5-based testing from the main branch (originally introduced for Flink 2.0 support) to Iceberg versions 1.19 and 1.20. This change simplifies the test environment, improves maintainability, and ensures compatibility with modern Flink and JUnit testing practices.
- → **Main Branch Merge Date: May 28, 2025**
  
<br>

### [2. 🍃 Spring/Kafka](https://github.com/spring-projects/spring-kafka)<br/>
#### [2.2. PR: GH-3514: Change Default Template Bean Name](https://github.com/spring-projects/spring-kafka/pull/3543)
- **Fix:** Replaced `retryTopicDefaultKafkaTemplate` with `RetryTopicBeanNames.DEFAULT_KAFKA_TEMPLATE_BEAN_NAME` in test code.
- **Documentation:** Updated docs to correctly reflect the default bean name as `defaultRetryTopicKafkaTemplate`.
- → **Main Branch Merge Date: October 19, 2024**
<br>
<h2> 🎨 My Toy Projects </h2>

- 🍔 **Food Delivery Service**: [daehong-food-delivery](https://github.com/JeonDaehong/daehong-food-delivery)
- 🤖 **Scenario Generator Using GPT API**: [scenario-gpt-project](https://github.com/JeonDaehong/scenario-gpt-project)

<br>
<h2> 📜 Certifications </h2>

- ✏️ **Engineer Information Processing Certificate** (Acquired: November 15, 2023)
- ✏️ **Linux Master** (Acquired: January 3, 2025)
