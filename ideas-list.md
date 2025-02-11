# 💡 Google Summer of Code - Project Ideas List  

Welcome to the **Google Summer of Code (GSoC) Project Ideas List** for **WSO2**! 🚀  

📌 **Before applying, students should:**  
- Read the [official GSoC guidelines](https://google.github.io/gsocguides/student/) on selecting a project.  
- Choose an idea that aligns with their skills and interests.  
- Reach out to mentors for guidance before submitting a proposal.  

---

## 📂 Project Ideas  

### Summary of Projects

Identity and Access Management:
- OpenID Connect Client Initiated Backchannel Authentication (CIBA) SDK with Python
- Financial-Grade API (FAPI) SDK
- Improve OAuth2/OIDC SDK with OAuth2 Rich Authorization Requests specification

Healthcare and Language Processing:
- OpenEHR Specification Library in Ballerina

API Management and Analytics:
- AI-Powered Analytics and Insights for WSO2 API Manager

### 🚀 1. **OpenID Connect Client Initiated Backchannel Authentication (CIBA) SDK with Python** 

**📅 Project Duration:** Long (~350 hours)  
**🔥 Difficulty Level:** Easy  
**👨‍🏫 Mentors:** Thilina Shashimal Senarath (thilinas@wso2.com), Omindu Rathnaweera (omindu@wso2.com)

**📍 Description:** 
This project aims to develop a Python SDK that simplifies the implementation of the Client-Initiated Backchannel Authentication (CIBA) flow, as defined in the OpenID Connect (OIDC) specification. CIBA enables authentication processes where the end user interacts with a dedicated authentication device, separate from the client application, making it ideal for scenarios where the client device lacks a direct, secure interface for user interactions.

The SDK will abstract the complexities of interfacing with identity providers (IdPs) that support CIBA, including **WSO2 Identity Server** (WSO2 IS). WSO2 IS is an open-source identity and access management (IAM) solution designed to provide seamless authentication, authorization, and identity federation capabilities. By offering a streamlined, easy-to-integrate solution for initiating and managing backchannel authentication requests, the SDK ensures interoperability with any compliant IdP while enhancing overall security and usability.

Note that familiarity with the specification is not a prerequisite for the project.

**🛠 Possible Technologies involved:** 
- Python
- OAuth/OIDC protocols
- Identity and Access Management

**📚 Learning Materials:**
- https://openid.net/specs/openid-client-initiated-backchannel-authentication-core-1_0-final.html
- https://ob.docs.wso2.com/en/latest/learn/ciba/	
- https://ob.docs.wso2.com/en/latest/develop/mobile-application-for-ciba/ 

**💪 Expected skills and technologies for the project:**
- Good understanding of Python programming language and its best practices. 
- Understanding of CIBA specification
- Understanding of WSO2 IS CIBA Flow

---

### 🚀 2. **Financial-Grade API (FAPI) SDK**  

**📅 Project Duration:** Long (~350 hours)  
**🔥 Difficulty Level:** Easy  
**👨‍🏫 Mentors:** Rivindu Madushan (rivindu@wso2.com), Madhavi Gayathri (madhavig@wso2.com)

**📍 Description:** 
This project focuses on developing a TypeScript SDK that enables secure and seamless integration with Identity Providers (IdPs) supporting the Financial-Grade API (FAPI) standard. FAPI is designed to provide enhanced security, privacy, and interoperability for financial and high-security applications, making it ideal for use cases in open banking, fintech, and other regulated industries.

The SDK will simplify the implementation of OAuth 2.0 and OpenID Connect (OIDC) flows compliant with FAPI, ensuring strong authentication, secure authorization, and fine-grained access control. It will offer built-in support for sender-constrained access tokens (MTLS/DPOP), Pushed Authorization Requests (PAR), Rich Authorization Requests (RAR), and advanced token handling mechanisms.

While optimized for integration with WSO2 Identity Server (WSO2 IS), this SDK will be designed to work with any IdP that complies with the FAPI standard, allowing developers to build secure and scalable applications across different IAM ecosystems. By abstracting the complexities of FAPI-compliant authentication and authorization, the SDK will provide developers with a streamlined, easy-to-use solution for implementing high-assurance API security in their applications.
Note that familiarity with the specification is not a prerequisite for the project.

**🛠 Possible Technologies involved:** 
- TypeScript
- OAuth/OIDC protocols
- Identity and Access Management

**📚 Learning Materials:**
- https://openid.net/wg/fapi/specifications/
- https://is.docs.wso2.com/en/latest/references/financial-grade-api/

**💪 Expected skills and technologies for the project:**
- Strong proficiency in the TypeScript programming language, along with best practices for scalable and maintainable development.
- Ability to read and interpret the Financial-Grade API (FAPI) specifications, ensuring compliance with security and interoperability standards.

---

### 🚀 3. **Improve OAuth2/OIDC SDK with OAuth2 Rich Authorization Requests specification**  

**📅 Project Duration:** Medium-term (~175 hours)  
**🔥 Difficulty Level:** Easy
**👨‍🏫 Mentors:** Vimukthi Rajapaksha (vimukthir@wso2.com), Lalaji Sureshika (lalaji@wso2.com)

**📍 Description:** 
This project focuses on improving the current react JS based SDK on OIDC to improve supporting OAuth2 Rich Authorization Requests(RAR) with supporting fine grained scopes, making it ideal for use cases in open banking, fintech, and other regulated industries.

The SDK will improve current SDK supporting OAuth 2.0 and OpenID Connect (OIDC) flows to support OAuth2 RAR  which will provide  built-in support for fine-grained access control.

While optimized for integration with WSO2 Identity Server (WSO2 IS), this improvement for the SDK will be designed to work with any IdP that complies with the OIDC, OAuth2 RAR standards, allowing developers to build secure and scalable applications across different IAM ecosystems. By abstracting the complexities of OAuth2 RAR authorization, the improvement on the SDK will provide developers with a streamlined, easy-to-use solution for implementing high-assurance API security in their applications.

Note that familiarity with the specification is not a prerequisite for the project.

**🛠 Possible Technologies involved:** 
- ReactJS
- OAuth/OIDC protocols
- Identity and Access Management

**📚 Learning Materials:**
- https://datatracker.ietf.org/doc/html/rfc9396
- https://is.docs.wso2.com/en/latest/complete-guides/react/install-asgardeo-sdk/

**💪 Expected skills and technologies for the project:**
- Good understanding  in the ReactJS programming language, along with best practices.
- Ability to read and interpret the OAuth2 RAR specification, to understand how it can connect with OIDC flow.

---

### 🚀 4. **OpenEHR Specification Library in Ballerina**  

**📅 Project Duration:** Medium-term (~175 hours)  
**🔥 Difficulty Level:** Easy
**👨‍🏫 Mentors:** Sameera Gunarathne (sameerag@wso2.com), Isuru Samaranayake (isurus@wso2.com)

**📍 Description:** 
This project aims to develop a Ballerina-based library that provides foundational support for working with OpenEHR specifications. OpenEHR is an open standard for electronic health record (EHR) data, ensuring structured, semantically interoperable health information. The goal is to create a lightweight library that enables Ballerina applications to parse, validate, and interact with OpenEHR-compliant data structures.
The implementation will focus on:
- Basic OpenEHR Model Support: Implement key OpenEHR reference model (RM) records such as EHR, Composition, Observation, and Archetype.
- Parsing and Serialization: Enable JSON/XML-based serialization and deserialization of OpenEHR data.
- Basic Query Handling: Implement a minimal AQL (Archetype Query Language) processor for simple data retrieval.
- Interoperability Support: Implement interoperability support with FHIR including OpenEHR to FHIR mapping library functions, OpenEHR client. 

While this project will not cover the full OpenEHR standard, it will establish the necessary foundations for further development and real-world adoption in healthcare applications.

**🛠 Possible Technologies involved:** 
- Ballerina (for developing the library)
- OpenEHR Specifications
- JSON/XML Processing

**📚 Learning Materials:**
- https://ballerina.io/
- https://specifications.openehr.org/
- https://specifications.openehr.org/releases/QUERY/latest/AQL.html


**💪 Expected skills and technologies for the project:**
- Basic knowledge of Ballerina programming language
- Understanding of OpenEHR concepts (Archetypes, Templates, and AQL)
- Ability to work with JSON and XML data structures

---

### 🚀 5. **AI-Powered Analytics and Insights for WSO2 API Manager**  

**📅 Project Duration:** Medium-term (~175 hours)  
**🔥 Difficulty Level:** Easy
**👨‍🏫 Mentors:** Pubudu Gunatilaka (pubudug@wso2.com), Arshardh Ifthikar (arshardh@wso2.com)

**📍 Description:** 
WSO2 API Manager is a full-lifecycle API management solution that enables organizations to create, publish, monitor, and secure APIs. A crucial aspect of API management is analytics, which provides visibility into API usage, performance, and security. Currently, WSO2 API Manager supports analytics through WSO2 Choreo, ELK (Elasticsearch, Logstash, and Kibana), and other third-party observability tools.

This project focuses on enhancing API analytics by integrating AI-powered insights, allowing users to interact with API analytics using natural language, predict traffic patterns, and analyze developer behavior for optimization.

The scope of this project is
- Natural Language Query Interface
    - Enable users to query API analytics using natural language.
    - Generate insightful visualizations based on user queries.
- Predictive Traffic Forecasting
    - Use historical API traffic data to forecast future API demand.
    - Help API providers proactively scale resources to handle peak loads.
- Developer Behavior Analysis
    - Identify inefficient API usage patterns (e.g., redundant API calls).
    - Provide recommendations to optimize API usage and improve performance.
    - Generate actionable insights for API publishers and consumers.

**🛠 Possible Technologies involved:** 
- WSO2 API Manager
- Natural Language Processing (OpenAI, BERT, or similar models)
- Data Visualization (Grafana, Kibana, or custom dashboards)

**📚 Learning Materials:**
- https://apim.docs.wso2.com/en/latest/
- https://apim.docs.wso2.com/en/latest/api-analytics/choreo-analytics/getting-started-guide

**💪 Expected skills and technologies for the project:**
- Basic knowledge of REST APIs
- Familiarity with NLP and AI-driven data insights.
- Experience with data visualization and dashboard development.

---

📌 **More project ideas coming soon!**  
📞 For any questions, reach out to mentors or check our [CONTRIBUTING.md](./CONTRIBUTING.md) guide.  

🚀 **Happy coding!**  
