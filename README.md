# **Masters' Thesis Project: Enhancing the security of Hybrid (DRAM/NVM) Memory Systems using AI-driven Page Migration**

## **Overview**
This repository contains the code, resources, and documentation for my Master’s Thesis Project at IIT Guwahati. The project is focused on enhancing the security of hybrid memory systems, specifically DRAM/NVM systems, by developing and implementing AI-driven techniques to prevent malicious write attacks that exploit NVM’s limited write endurance. The ultimate goal is to safeguard the integrity and longevity of hybrid memory systems.

## **Problem Statement**
Hybrid memory systems, which combine the high speed of DRAM with the non-volatility of NVM, are increasingly being used in modern computing architectures. However, NVM has a critical limitation: its endurance is significantly lower than that of DRAM, making it susceptible to wear-out when subjected to excessive write operations.

Malicious software can exploit this by intentionally writing to the same memory location repeatedly, causing that location to degrade rapidly. This can lead to the failure of the entire NVM module, compromising the system’s data integrity. My thesis addresses this security challenge by proposing a solution that uses AI to detect these malicious write patterns and mitigate their impact through a dynamic page migration strategy.

## **Project Objectives**
1. **Identify and Mitigate Write Attacks:**
   - Develop machine learning models that can detect abnormal memory access patterns indicative of potential write attacks targeting NVM’s limited endurance.

2. **AI-Driven Page Migration:**
   - Implement a page migration mechanism that automatically transfers frequently accessed pages from NVM to DRAM, thereby protecting NVM from excessive wear and ensuring data integrity.

3. **Validation and Testing:**
   - Validate the effectiveness of the proposed solution through comprehensive testing using the gem5 simulator across various benchmarks and applications.

## **Technologies and Tools**
- **Programming Languages:** C, C++
- **Simulation Tool:** gem5
