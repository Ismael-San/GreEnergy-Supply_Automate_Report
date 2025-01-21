# GreEnergy - CleanEnergy Automate Report

## Table of Contents

* [Overview](#project-overview)
* [Project Background](#project-background)
* [Business Case Request from Head of Operations](#Business-Case-Request-from-Head-of-Operations)
* [Data Structure](#data-structure)
* [Certificate Delivery Conditions](#certificate-delivery-conditions)
* [Caveats & Assumptions](#caveats-assumptions)

## Project Overview

## **The goal of this project is to provide valuable insights into the sales performance of a e-commerce company over the past year. By analyzing various aspects of the sales data such as revenue, customer behaviour and product-level performance, we aim to identify patterns, implement effective solutions and produce data-driven recommendations for its marketing and sales teams.** Template

## ** The project’s goal here was to (provide/create find the most suitable verb) an automate report for each site present in XXX database. By using client’s data (Info-Equilibrage-Température and photos folders; Chaufferie - Pompes - Vannes, we aim to generate a Python code that will generate automatic report. XXX assigned to us this mission in order to increase the generation of reports and facilitate the obtention of “white certificate”, and hence achieved goal fixed by the government and so reduce the energy (fossil) consumption. ** 

## Project Background

Greenery - CleanEnergy est un fournisseur d’énergie spécialisé dans la fourniture d’énergie et d’équipement à faible consommation (d’energie). Le gouvernement a promulgué en (XXX) la loi POPE ; obligeant les fournisseurs d’énergie à atteindre un objectif en terme de volume TWhcumac selon la période (2022-2025 = 5th period - 3100 TWhcumac) ceci afin lutter face aux crises et dérèglements climatiques que nous subissons à l’échelle mondiale. 

C’est pourquoi les fournisseurs proposent un système de financement auprès des (cibles - propriétaire de logement) dans le but effectuer des travaux de rénovation et donc réduire l’empreinte carbone (more precise). Les fournisseurs reçoivent alors un Certificat d’Économie d’Énergie en contre-partie du financement des rénovation, attestant (l’économie d’énergie réalisée) l’effort fournit en terme d’économie d’énergie.

Plusieurs types d’équipement et d’installation permettent l’obtention de ces certificats CEE, GreenEnergy / CleanEnergy se focalise sur celle de type BAR SE-104; le “réglage des organes d’équilibrage d’une installation de chauffage à eau chaude”  procédure centrée sur une répartition équilibrée de la chaleur dans différents logements…

In order the sales and marketing teams have engaged our expertise as data analysts to leverage data collected over the past year. The analysis aims to provide a deeper understanding of sales performance across product types and customer segments, and to support impactful decision-making for strategy development.

**In order to evaluate sales performance, we focused our insights and recommendations on the following key metrics:**

* **Sales Trend Analysis**: Assessment of sales patterns by product and customer, focusing on Revenue, Average Order Value (AOV), and Order Volume.
* **Product-Level Performance**: In-depth analysis of product trends during the period to understand their impact on sales.
* **Customer Segmentation**: Evaluation of customer behavior by age range and loyalty membership.

## Business Case Request from Head of Operations

"Hello Ismael,

I hope you are doing well,

Well 5th period is coming to the end and our energy-product team is currently preparing a detailed-report (compte rendu) that retrieves all interventions related to BAR SE-104 operations towards/concerning our clients. In order to be eligible and collect the CEE delivered by the government, we need to generate, for each site, a singular report that regroups justified document specific to the operation such as client’s data, photos (boiler, pump etc…) 

*comme présence de conditions requises notamment la présence de document justificatifs pour la délivrance de certificats - 

Can you please help us providing a Python script code that will automatically generate individual report for each of our clients based on their data collected inside our database. 

Here is a deeper look of elements that compose  “site” folder that I have attached:

- a folder called “Site_Data” that regroup clients information in excel files (”données_clients” file that contains three sheets : Info - Équilibrage - Températures
- “Images” folder which/that contains client photos of different pieces “Chaufferie”, “Façade”, “Vannes”, “Pompes” that you will need to replace in the template report
- A PDF file that you will use as template (page 1 - 5 - 7 - 8 - 10 need modification for each client - the rest is unchanged)

Additional information: each client’s file are located in a file called “REPORT_EQ_23(23 correspond to the year)/T1(= trimester)/R122( = report number)-Site_Name”

Feel free to send any questions in the meantime,

Looking forward to hearing from you,

Gabrielle”

## Data Structure

An interactive Tableau Desktop dashboard can be found [here](https://public.tableau.com/app/profile/ismael.cisse/viz/ElecTechAnalysis/ExecutiveOverview?publish=yes).
The Python file utilised to clean, organize, and prepare data for the dashboard can be found here(insert link).

(Insert Screen of Dataset - from Python)

## Certificate Delivery Conditions

## Caveats & Assumptions
