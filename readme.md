#### REMINDER
### Proyecto AWS_SAAC-003

Este repositorio contiene código y recursos relacionados con el curso **AWS Certified Solutions Architect - Associate (SAA-C03)** impartido por **Adrian Cantrill**. Todo el contenido de este repositorio ha sido creado siguiendo su curso y las instrucciones proporcionadas en el mismo.

### Autoría

El código y las ideas reflejadas en este repositorio pertenecen completamente a **Adrian Cantrill**, quien ha desarrollado el contenido de manera original a través de su curso.

### Curso de Adrian Cantrill en AWS Certified Solutions Architect - Associate (SAA-C03)

Para más información o para acceder al curso, puedes visitar los siguientes enlaces:

- [AWS Certified Solutions Architect - Associate (SAA-C03) en AdrianCantrill.com](https://learn.cantrill.io/p/aws-certified-solutions-architect-associate-saa-c03)
- [AWS Certified Solutions Architect - Associate (SAA-C03) en Udemy](https://www.udemy.com/course/aws-certified-solutions-architect-associate/)
- [Repositorio learn-cantrill-io-labs](https://github.com/acantril/learn-cantrill-io-labs/tree/master)

Agradecimientos especiales a Adrian Cantrill por compartir su conocimiento y contribuir al éxito de quienes buscan certificarse en AWS.

## Uso del Repositorio

Este repositorio se utiliza con fines educativos siguiendo las directrices del curso de **Adrian Cantrill**. Se recomienda no utilizar el contenido con fines comerciales ni distribuirlo sin la debida atribución.

---

### AWS_SAAC-003 Project

This repository contains code and resources related to the **AWS Certified Solutions Architect - Associate (SAA-C03)** course taught by **Adrian Cantrill**. All the content in this repository has been created following his course and instructions.

### Attribution

The code and ideas reflected in this repository fully belong to **Adrian Cantrill**, who originally developed the content through his course.

### Adrian Cantrill's AWS Certified Solutions Architect - Associate (SAA-C03) Course

For more information or to access the course, you can visit the following links:

- [AWS Certified Solutions Architect - Associate (SAA-C03) on AdrianCantrill.com](https://learn.cantrill.io/p/aws-certified-solutions-architect-associate-saa-c03)
- [AWS Certified Solutions Architect - Associate (SAA-C03) on Udemy](https://www.udemy.com/course/aws-certified-solutions-architect-associate/)
- [Learn-cantrill-io-labs repository](https://github.com/acantril/learn-cantrill-io-labs/tree/master)

Special thanks to Adrian Cantrill for sharing his knowledge and contributing to the success of those seeking AWS certification.

### Repository Usage

This repository is used for educational purposes following the guidelines of **Adrian Cantrill's** course. It is recommended not to use the content for commercial purposes or distribute it without proper attribution.


# Advanced Demo - Simple Site2Site VPN

![Architecture](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-simple-site2site-vpn/Architecture.png)

In this mini project you will implement a site to site VPN between AWS and a simulated on-premises business site running the pfSense router/NAT software.

The demo consists of 5 stages, each implementing additional components of the architecture  

- Stage 1 - Create Site2Site VPN
- Stage 2 - Configure onpremises Router  
- Stage 3 - Routing & Security
- Stage 4 - Testing
- Stage 6 - Cleanup

## 1-Click Install

- Make sure you are logged into AWS and in `us-east-1`
- you will need to approve this [subscription](https://aws.amazon.com/marketplace/pp?sku=cphb99lr7icr3n9x6kc3102s5) it's a trial, so you won't be billed anything extra. 
- You will need to have an SSH keypair created in `us-east-1` and select this when using the 1-click deployment below
- Once approved, you can use the one click deployment below.

- [SimpleSite2SiteVPN](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://learn-cantrill-labs.s3.amazonaws.com/aws-simple-site2site-vpn/infra.yaml&stackName=S2SVPN)  (**be sure to select a keypair**)

## Instructions

- [Stage1 - Create Site2Site VPN](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE1.md)
- [Stage2 - Configure onpremises Router](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE2.md)
- [Stage3 - Routing & Security](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE3.md)
- [Stage4 - Testing](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE4.md)
- [Stage5 - Cleanup](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE5.md)

## Video Guides

- [STAGE0](https://youtu.be/v9PactTXMTQ)
- [STAGE1](https://youtu.be/oizexSe2ajQ)
- [STAGE2](https://youtu.be/2LZRxc7UZns)
- [STAGE3](https://youtu.be/mUgXjnAJHFA)
- [STAGE4](https://youtu.be/RjietVauypA)
- [STAGE5](https://youtu.be/yMb1UXqwsCA)

## Architecture Diagrams

- [Stage0](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE0.pdf)
- [Stage1](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE1.pdf)
- [Stage2](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE2.pdf)
- [Stage4](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-simple-site2site-vpn/02_LABINSTRUCTIONS/STAGE4.pdf)
