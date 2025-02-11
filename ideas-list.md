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

📌 **More project ideas coming soon!**  
📞 For any questions, reach out to mentors or check our [CONTRIBUTING.md](./CONTRIBUTING.md) guide.  

🚀 **Happy coding!**  
