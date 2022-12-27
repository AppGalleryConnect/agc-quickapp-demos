#  Cloud DB JS SDK Demo


## Introduction
This project is a quick start sample developed using Cloud DB JS SDK.

## Quick Start
- On the [AppGallery Connect](https://developer.huawei.com/consumer/en/service/josp/agc/index.html#/myProject) page, create a project and add an application.

- Click **Auth Service** on the navigation bar and enable authentication using an anonymous account.

- Click **Cloud DB** on the navigation bar and enable database service. Then, perform the following operations:

  （1）Create a schema by importing a template file stored in **BookInfo.json** in the `config/` directory of the project. Alternatively, create a object type named **BookInfo** and ensure that all fields must be the same as those in `module/BookInfo.js` of the project.

  （2） Create a Cloud DB zone. On the **Cloud DB Zone** tab page, click **Add** to create a Cloud DB zone named **QuickStartDemo**.


- On the Project Setting page, obtain the app configuration information. Save it to the context object in the `config/agconnect-services.json` file.

- Integrate the Cloud DB SDK.

  Run the following command to install the Cloud DB JavaScript SDK service module in the root directory:

  ```
    npm install
  ```

## Operate Data

##### 1. Login anonymous.

![Login](src/assets/images/login1.PNG)
![Login](src/assets/images/login2.PNG)

##### 2. Input zone name `QuickStartDemo` and click the `enter` button to open Cloud DB zone.

![OpenZone](src/assets/images/openZone1.PNG)
![OpenZone](src/assets/images/openZone2.PNG)

##### 3. Insert a record.

![Insert](src/assets/images/insert1.PNG)
![Insert](src/assets/images/insert2.PNG)

##### 4. Update a record.

![Update](src/assets/images/update1.PNG)
![Update](src/assets/images/update2.PNG)

##### 5. Delete a record.

![Delete](src/assets/images/delete.PNG)

##### 6. Query records.

![Query](src/assets/images/query.PNG)
