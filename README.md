# GreEnergy - CleanEnergy Automate Report

## Table of Contents

* [Overview](#project-overview)
* [Project Background](#project-background)
* [Business Case Request from Head of Operations](#Business-Case-Request-from-Head-of-Operations)
* [Data Structure](#data-structure)
* [Certificate Delivery Conditions](#certificate-delivery-conditions)
* [Caveats & Assumptions](#caveats-assumptions)

## Project Overview

## **Project's goal here is to develop an automated report generation file for each client's site listed in the GreEnergy-Supply database, as well as future ones. GreEnergy-Supply has entrusted us with this mission to streamline the report generation process in order to facilitate the acquisition of "White certificate" in compliance with delivery conditions. This initiative aims to meet government targets for energy savings, 3100 TWhcumac currently (5th period 2022-2025) by increasing the use of renewable energy or reduce energy consumption from fossil fuels.** 

## Project Background

GreEnergy-Supply is a french energy supplier specializing in equipment and provide of renewable and thermal energy. The French Govermennt, which has established political measures towards energy transition with P.O.P.E law in 2005, is conducting a high political pressure towards energy suppliers in order to reduce energy consumption. As we ended the 5th period (2022-2025), the energy savings target has been fixed to 3100 TWhcumac (amount splited between energy supplier), a unit mesure of energy saving where 1kWh cumac represents a singular "White Certificate". 

White Certificate or Energy Savings Certificate (ESC) is supplier's "gold ticket" that guarantees its efforts in reducing energy consumption and the exemption from taxes as well. To support this they initiate incitative energy-improvement interventions in their equipment by offering funds to their clients, whether their statut (private or companies) or if it concerns thermal or electrical fields. 

These certificates cover a huge selection of interventions and applications. GreEnergy-Supply is focusing on BAR SE-104: "Balancing Heating System" a process that guarantees a balanced distribution of heat across different appartment.

To achieve this, the energy-product section has engaged our expertise as data analysts to leverage data collected from each site that is eligible for BAR SE-104 certificate delivery. The mission aims to generate Python code that will automatically create a report for each site based on the elements required to obtain the Energy Savings Certificate.

accelerate transition and accomplish objectives dressed by the government in terms of TWhcumac 



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
