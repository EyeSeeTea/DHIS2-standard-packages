# WHO Configuration Packages for DHIS2
The WHO configuration packages consist of DHIS2 metadata that provide standard configurations of DHIS2 to support the collection of health data following WHO recommendations. 

# Entomology and Vector Control
Generic DHIS2 modules have been developed to strengthen the collection, reporting and use of malaria entomology and vector control data to inform decision-making. All the modules have been designed in line with existing WHO recommendations, standard protocols and guidance.
These modules complement already existing [modules for malaria epidemiology](https://who.dhis2.org/documentation/index.html#malaria).

The modules consist consist of event programs and dashboards to support the collection of data from the following activities:
  * ITN mass distribution campaigns, 
  * ITN bioefficacy monitoring, 
  * IRS campaigns, 
  * IRS residual efficacy monitoring, 
  * insecticide resistance monitoring, 
  * adult mosquito surveillance and identification, including individual mosquito laboratory results
  * monitoring of mosquito larval habitats.

A **[demo of the modules](https://extranet.who.int/dhis2-ento-vc)** is available in french and english.

More information on the modules and the tools designed to facilitate their implementation can be found in [this page](https://www.who.int/teams/global-malaria-programme/prevention/vector-control/dhis-data-collection-and-collation-tools)

Links to the latest version of the metadata packages compatible with different DHIS2 versions included in the tables below. If you have questions or difficulties implementing these modules, please contact fernandezl@who.int

## Insecticide Resistance monitoring
| Module name | DHIS2 Version | Package Version | Package Type |  Metadata | Last updated |
| --- | --- | --- | --- |  --- | --- |
| Discriminating concentration bioassays |  DHIS2.34 | V0.0.2 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20DISCRIMINATING/ENTO-IR_DIS_metadata_program-0.0.2-2.34-202011131444.json)	| 2020-11-18 |
| |  DHIS2.33 | V0.0.2 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20DISCRIMINATING/ENTO-IR_DIS_metadata_program-0.0.2-2.33-202011131444.json)	| 2020-11-18 |
|  |  DHIS2.32 | V0.0.2 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20DISCRIMINATING/ENTO-IR_DIS_metadata_program-0.0.2-2.32-202011131444.json)	| 2020-11-18 |
| |  DHIS2.31 | V0.0.2 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20DISCRIMINATING/ENTO-IR_DIS_metadata_program-0.0.2-2.31-202011131444.json)	| 2020-11-18 |
| Discriminating concentration bioassays + individual mosquito tracker |  DHIS2.34 | V0.0.0 | Event + Tracker Linked Programs |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-IR%20DISCRIMINATING%20%2B%20MOSQUITO%20TRACKER%20BIOASSAY/ENTO-DISCRIMINATING%2BMOSQUITO%20TRACKER%20BIOASSAY_metadata_program-0.0.0-2.34-20200121.json)	| 2021-01-21 |
| Discriminating concentration bioassays (with individual replicates) |  DHIS2.35 | V0.0.2 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-IR%20DISCRIMINATING/ENTO-IR_DIS_metadata_program_replicates-0.0.2-2.35-202106231741.json)	| 2021-07-20 |
| Intensity concentration bioassays | DHIS2.34 | V1.0.6 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20INTENSITY/ENTO-IR_INT_metadata_program-1.0.6-2.34-202011171244.json) | 2020-11-18 |
|  | DHIS2.33 | V1.0.6 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20INTENSITY/ENTO-IR_INT_metadata_program-1.0.6-2.33-202011171244.json) | 2020-11-18 |
|  | DHIS2.32 | V1.0.6 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20INTENSITY/ENTO-IR_INT_metadata_program-1.0.6-2.32-202011171244.json) | 2020-11-18 |
|  | DHIS2.31 | V1.0.6 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20INTENSITY/ENTO-IR_INT_metadata_program-1.0.6-2.31-202011171244.json) | 2020-11-18 |
| Intensity concentration bioassays + individual mosquito tracker | DHIS2.34 | V0.0.1 | Event + Tracker Linked Programs | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-IR%20INTENSITY%20%2B%20MOSQUITO%20TRACKER%20BIOASSAY/ENTO-IR%20INTENSITY%20%2B%20MOSQUITO%20TRACKER%20BIOASSAY-0.0.1-2.34-202101211013.json) | 2021-01-21 |
| Intensity concentration bioassays (with replicates) | DHIS2.35 | V1.0.6 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-IR%20INTENSITY/ENTO-IR-ITN_metadata_program_replicates-1.0.6-2.35-202106231801.json) | 2021-07-20 |
| Synergist-insecticide bioassays | DHIS2.34 | V0.0.5| Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20SYNERGIST/ENTO-IR_SYN_metadata_program-0.0.5-2.34-202011181316.json) | 2020-11-18 |
|  | DHIS2.33 | V0.0.5 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20SYNERGIST/ENTO-IR_SYN_metadata_program-0.0.5-2.33-202011181316.json) | 2020-11-18 |
|  | DHIS2.32 | V0.0.5 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20SYNERGIST/ENTO-IR_SYN_metadata_program-0.0.5-2.32-202011181316.json) | 2020-11-18 |
|  | DHIS2.31 | V0.0.5 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20SYNERGIST/ENTO-IR_SYN_metadata_program-0.0.5-2.31-202011181316.json) | 2020-11-18 |
| Synergist-insecticide bioassay + individual mosquito tracker | DHIS2.34 | V0.0.0 | Event + Tracker Linked Programs | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-IR%20SYNERGIST%20%2B%20MOSQUITO%20TRACKER%20BIOASSAY/ENTO-IR%20SYNERGIST%20%2B%20MOSQUITO%20TRACKER%20BIOASSAY-0.0.0-2.34-202101211018.json) | 2021-01-21 |
| Synergist-insecticide bioassays (with replicates) | DHIS2.35 | V0.0.5| Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-IR%20SYNERGIST/ENTO-IR_SYN_metadata_program_replicates-0.0.5-2.35-202106231659.json) | 2021-07-20 |
| Resistance Mechanisms | DHIS2.34 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20MECHANISMS/ENTO-IR_MECH_metadata_program-0.0.2-2.34-202011181315.json) | 2020-11-18 |
|  | DHIS2.33 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20MECHANISMS/ENTO-IR_MECH_metadata_program-0.0.2-2.33-202011181315.json) | 2020-11-18 |
|  | DHIS2.32 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20MECHANISMS/ENTO-IR_MECH_metadata_program-0.0.2-2.32-202011181315.json) | 2020-11-18 |
|  | DHIS2.31 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-IR%20MECHANISMS/ENTO-IR_MECH_metadata_program-0.0.2-2.31-202011181315.json) | 2020-11-18 |

## Adult surveillance
| Module name | DHIS2 Version | Package Version | Package Type |  Metadata | Last updated |
| --- | --- | --- | --- |  --- | --- |
| Adult surveillance |  DHIS2.34 | V0.0.0 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-ADULT%20SURVEILLANCE/ENTO-ADULT_SURV_metadata_program-0.0.0--2.34-202010092218.json)	| 2020-10-13 |
| Mosquito Tracker | DHIS2.35 | V0.0.7 | Linked Tracker Programs (x2) | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-MOSQUITO%20TRACKER/ENTO-MOSQUITO%20TRACKER-0.0.7-2.35-202103260029.json) | 2021-03-26 |
|  | DHIS2.34 | V0.0.7 | Linked Tracker Programs (x2) | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-MOSQUITO%20TRACKER/ENTO-MOSQUITO%20TRACKER-0.0.7-2.34-202103260029.json) | 2021-03-26 |
|  | DHIS2.33 | V0.0.7 | Linked Tracker Programs (x2) | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-MOSQUITO%20TRACKER/ENTO-MOSQUITO%20TRACKER-0.0.7-2.33-202103260029.json) | 2021-03-26 |

## Breeding sites monitoring
| Module name | DHIS2 Version | Package Version | Package Type |  Metadata | Last updated |
| --- | --- | --- | --- |  --- | --- |
| Breeding sites maping |  DHIS2.34 | V0.0.1 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/ENTO-BREEDING%20SITES/ENTO-BREED_SITE_MAPING_metadata_program-0.0.1-2.34-202010201051.json)	| 2020-10-20 |
| Breeding sites tracker |  DHIS2.34 | V0.0.0 | Tracker Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/ENTO-BREEDING%20SITES%20TRACKER/ENTO-BREED_SITE_TRACKER_metadata_program-0.0.3-2.34-20201021.json)	| 2021-01-21 |

## Indoor Residual Spraying (IRS)
| Module name | DHIS2 Version | Package Version | Package Type |  Metadata | Last updated |
| --- | --- | --- | --- |  --- | --- |
| IRS Campaign totals |  DHIS2.34 | V0.0.4 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20CAMPAIGN%20TOTALS/ENTO-VC_IRS_metadata_program-0.0.4-2.34-202011181318.json)	| 2020-11-18 |
|  |  DHIS2.33 | V0.0.4 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20CAMPAIGN%20TOTALS/ENTO-VC_IRS_metadata_program-0.0.4-2.33-202011181318.json)	| 2020-11-18 |
|  |  DHIS2.32 | V0.0.4 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20CAMPAIGN%20TOTALS/ENTO-VC_IRS_metadata_program-0.0.4-2.32-202011181318.json)	| 2020-11-18 |
|  |  DHIS2.31 | V0.0.4 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20CAMPAIGN%20TOTALS/ENTO-VC_IRS_metadata_program-0.0.4-2.31-202011181318.json)	| 2020-11-18 |
| IRS Residual efficacy| DHIS2.35 | V0.0.1 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages-nonHF/blob/GMP/VCR/VC-IRS%20RESIDUAL%20EFFICACY/ENTO-VC_RES_metadata_program-0.0.1-2.35_202106231710.json) | 2021-07-20 |
| | DHIS2.34 | V0.0.1 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20RESIDUAL%20EFFICACY/ENTO-VC_RES%20_metadata_program-0.0.1-2.34-202011061943.json) | 2020-11-18 |
| | DHIS2.33 | V0.0.1 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20RESIDUAL%20EFFICACY/ENTO-VC_RES%20_metadata_program-0.0.1-2.33-202011061943.json) | 2020-11-18 |
| | DHIS2.32 | V0.0.1 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20RESIDUAL%20EFFICACY/ENTO-VC_RES%20_metadata_program-0.0.1-2.32-202011061943.json) | 2020-11-18 |
| | DHIS2.31 | V0.0.1 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-IRS%20RESIDUAL%20EFFICACY/ENTO-VC_RES%20_metadata_program-0.0.1-2.31-202011061943.json) | 2020-11-18 |

## Insecticide Treated Nets (ITNs)
| Module name | DHIS2 Version | Package Version | Package Type |  Metadata | Last updated |
| --- | --- | --- | --- |  --- | --- |
| ITN Campaign totals |  DHIS2.34 | V0.0.3 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20CAMPAIGN%20TOTALS/ENTO-IR_INT_metadata_program-0.0.3-2.34-202011131443.json)	| 2020-11-18 |
| |  DHIS2.33 | V0.0.3 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20CAMPAIGN%20TOTALS/ENTO-IR_INT_metadata_program-0.0.3-2.33-202011131443.json)	| 2020-11-18 |
| |  DHIS2.32 | V0.0.3 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20CAMPAIGN%20TOTALS/ENTO-IR_INT_metadata_program-0.0.3-2.32-202011131443.json)	| 2020-11-18 |
|  |  DHIS2.31 | V0.0.3 | Event Program |  [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20CAMPAIGN%20TOTALS/ENTO-IR_INT_metadata_program-0.0.3-2.31-202011131443.json)	| 2020-11-18 |
| ITN Bioefficacy |  DHIS2.35 | V0.0.2 | Event Program | [metadata.json](https://github.com/EyeSeeTea/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20BIOEFFICACY/ENTO-VC_ITN_BIO_metadata_program_0.0.2-2.35-202106231859.json) | 2021-07-20 |
|  |  DHIS2.34 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20BIOEFFICACY/ENTO-VC_ITN_BIO_metadata_program-0.0.2-2.34-202011061943.json) | 2020-11-18 |
|  |  DHIS2.33 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20BIOEFFICACY/ENTO-VC_ITN_BIO_metadata_program-0.0.2-2.33-202011061943.json) | 2020-11-18 |
|  |  DHIS2.32 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20BIOEFFICACY/ENTO-VC_ITN_BIO_metadata_program-0.0.2-2.32-202011061943.json) | 2020-11-18 |
| |  DHIS2.31 | V0.0.2 | Event Program | [metadata.json](https://github.com/WorldHealthOrganization/DHIS2-standard-packages/blob/GMP/VCR/VC-ITN%20BIOEFFICACY/ENTO-VC_ITN_BIO_metadata_program-0.0.2-2.31-202011061943.json) | 2020-11-18 |
