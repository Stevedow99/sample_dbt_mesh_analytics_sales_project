# dbt Cloud Mesh Sample Project - Sales Analytics Spoke Project
#### **_Note_**: dbt Cloud Mesh and Cross Project dbt References are features only in available in [dbt Cloud](https://www.getdbt.com/product/dbt-cloud) or with the [dbt Cloud CLI](https://docs.getdbt.com/docs/cloud/cloud-cli-installation), these features are not available in dbt Core (OSS dbt)
- If you need guidance converting your dbt Core project into dbt Cloud, use this [guide](https://docs.getdbt.com/guides/core-to-cloud-1?step=1) 

#### This repo is one of three repos used to demo and sample dbt Cloud mesh which includes:
- Cross Project dbt References
- dbt Model Contracts
- dbt Model Governance


## dbt Project Level dependencies (as shown in dbt Cloud Explorer)
 ![Project Level Dependencies](./documentation/dbt_cloud_mesh_all_projs.png)

## This projects showing the upstream dependency of the Data Engineering hub Project (as shown in dbt Cloud Explorer)
 ![Downstream Project with Upstream Dependencies](./documentation/dbt_cloud_mesh_sa.png)

## The Data Engineering project with downstream project dependencies including this project (as shown in dbt Cloud Explorer)
 ![Data Engineering With Downstream Dependencies](./documentation/dbt_cloud_mesh_de.png)
