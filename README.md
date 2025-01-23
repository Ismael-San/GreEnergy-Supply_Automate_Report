# GreEnergy - CleanEnergy Automate Report

## Table of Contents

* [Overview](#project-overview)
* [Project Background](#project-background)
* [Business Case Request from Head of Operations](#Business-Case-Request-from-Head-of-Operations)
* [Data Structure](#data-structure)
* [Certificate Delivery Conditions](#certificate-delivery-conditions)
* [Caveats & Assumptions](#caveats-assumptions)

## Project Overview

## **Project's goal here is to develop an automated report generation file for each client's site listed in the GreEnergy-Supply database, as well as future ones. GreEnergy-Supply has entrusted us with this mission to streamline the report generation process in order to facilitate the acquisition of "White certificate" in compliance with delivery conditions. This initiative aims to meet government targets for energy savings by increasing the use of renewable energy or reduce energy consumption from fossil fuels.** 

## Project Background

GreEnergy-Supply is a french energy supplier specializing in equipment and provide (or providing) of renewable and thermal energy. The French Govermennt, which has established political measures towards energy transition with the P.O.P.E (for Programme fixant les Opérations de la Politique Energétique) law in 2005, is conducting a high political pressure towards energy suppliers in order to reduce energy consumption. As we ended the 5th period (2022-2025), the energy savings target has been fixed to 3100 TWhcumac (amount splited between energy supplier), a unit mesure of energy saving where 1kWh cumac represents a singular "White Certificate". 

White Certificate or Energy Savings Certificate (ESC) is supplier's "golden ticket" that guarantees its efforts in reducing energy consumption and the exemption from taxes as well. To support this they initiate incitative energy-improvement interventions in their equipment by offering funds to their clients, whether their statut (private or companies) or if it concerns thermal or electrical fields. 

These certificates cover a huge selection of interventions and applications. GreEnergy-Supply is currently focusing on BAR SE-104 type: "Balancing Heating System" a process that guarantees a balanced distribution of heat across different appartment.

To achieve this, the product team has engaged my expertise as a data analyst to leverage data collected from GreEnergy-Supply's eligible clients (residential and tertiary buildings) for the certificate.
In more detail, the clients who received an energy-improvement intervention and have documentation certifying the energy savings obtained as a result of the measure are included.
The mission aims to generate an automated report using Python that meets certificate requirements, in order to facilitate and increase the acquisition of the 'White Certificate' and ultimately reach or surpass the energy savings targets set by the government.

## Business Case Request from Head of Operations

"Hello Ismael,

I hope you're doing well.

As the 5th period is nearing its end, our energy-product team is preparing a detailed report summarizing interventions related to BAR SE-104 operations with our clients. To be eligible for the CEE (Certificat d’Économies d’Énergie) granted by the government, we need to generate an individual report for each site. These reports will compile the necessary documentation that justifies the intervention and the energy savings.

Could you assist us by providing a Python script that will automatically generate the individual reports for each of our clients based on the data stored in our database?

Here is a breakdown of the elements included in the “site” folder that I have attached:

- “Site_Name” folder which contains an Excel file titled “données_clients.” This file has three sheets: Info, Équilibrage, and Températures, which include the relevant client data.
- “Images” folder that includes client photos of various components, such as boilers, valves and pumps, which need to be inserted into the template report.
- A PDF file serving as the template for the report

For your reference, each client’s file is located in a folder structure as follows: “.../REPORT_EQ_XX/TX/RXXX-Site_Name”.
Where "_XX/" represents the year, TX indicates the trimester and RXXX is the report number.

Please feel free to reach out with any questions in the meantime.

Looking forward to hearing from you.

Best regards,

Gabrielle“

## Data Structure

An interactive Tableau Desktop dashboard can be found [here](https://public.tableau.com/app/profile/ismael.cisse/viz/ElecTechAnalysis/ExecutiveOverview?publish=yes).
The Python file utilised to clean, organize, and prepare data for the dashboard can be found here(insert link).

(Insert Screen of Dataset - from Python)

```Python


```

## Certificate Delivery Conditions

## Caveats & Assumptions
