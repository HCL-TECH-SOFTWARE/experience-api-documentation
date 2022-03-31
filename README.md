# HCL Experience API Documentation

The HCL Experience API is a set of OpenAPI compliant REST APIs available for customers deploying HCL Digital Experience 9.5 containers on supported Kubernetes platforms. It supports the integration and management of HCL Digital Experience content and functionality to any digital channel using any front-end development framework. The HCL Experience API includes REST APIs that serve as a wrapper around previously published HCL Digital Experience HTTP based APIs.
The Experience API describes a high-level API through which the following specific APIs are exposed:

HCL Experience API

| Name                                                                   | Description                                                                                                                                                                            | Live API Explorer URL               |
|------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|
| [**_HCL Ring API _**](https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/ring-api)                      | Presents developer entry points to HCL DX 9.5 core platform capabilities which are divided into two main categories: Authorization APIs and Web Content APIs.                          | /dx/api/core/v1/explorer            |
| [**_HCL Digital Asset Management API _**](https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/dam-api)   | Presents developer entry points to the Digital Asset Management features of HCL DX 9.5.                                                                                                | /dx/api/dam/v1/explorer             |
| [**_HCL Image Processor API_**](https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/image-processor-api) | Presents developer entry points to the Digital Asset Management Image Processor functions of HCL DX 9.5.                                                                               | /dx/api/image-processor/v1/explorer |
| [**_HCL Personalization API_**](https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/pzn-api)             | Presents developer entry points to the Personalization Rule functions of HCL DX 9.5.                                                                                                   | /dx/api/pzn/v1/explorer             |
| [**_HCL WCM API_**](https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/wcm-api)                   | Presents redesigned developer entry points to the Web Content Manager functions of HCL DX 9.5. Intended to facilitate the management of Web content, content-sites, and content-pages. | /dx/api/wcm/v2/explorer             |

> **Note :** Future HCL DX 9.5 feature functionality will also be exposed through the HCL Experience API.

It is recommended that developers building solutions for HCL Digital Experience 9.5 running on Kubernetes programmatically use the HCL Experience API for the scenarios that are covered.

The HCL Experience API is a component of the HCL Digital Experience offerings. HCL Digital Experience offering license and download packages are provided with HCL Digital Experience entitlements available to customers on the HCL Software License Portal. https://www.hcltech.com/software/support/release

## Reference urls 

Documentation | URL Specification
--------------|------------------
HCL Ring API | https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/ring-api
HCL Digital Asset Management API | https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/dam-api
HCL Image Processor API | https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/image-processor-api
HCL Personalization API | https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/pzn-api
HCL WCM API | https://HCL-TECH-SOFTWARE.github.io/experience-api-documentation/wcm-api