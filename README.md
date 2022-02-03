<h1 align="center">
  <img src="./Eoghan.png" width="900px"/><br/><br/>
  Google Cloud Backend for a Flutter Mobile App.
</h1>
<p align="center">This is a <b>Google Cloud</b> Backend for a <b>Flutter</b> Video sharing platform.</p>

<br/>
<hr/>

## <p align="center">🏗 Services Used</p>

#### 🤚 Authentication

|                                                        |        Service       |                  Rationale                                                                                                                                                                                  |
| ------------------------------------------------------ | -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/firebase.png" width="40px" />       |    `Firebase Auth`   |  [Firebase Auth](https://firebase.google.com/docs/auth/) is strongly supported by Flutter it removes the hassle of integrating authentication services. It's ideal for Agile startups and it's widely used. |

<br/>


#### 🙎‍♀️ User Profile Management

|                                                        |       Service     |                  Rationale                                                                                                                                                                           |
| ------------------------------------------------------ | ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/firebase.png" width="40px" />       |  `Firebase Auth`  |  [Firebase Auth](https://firebase.google.com/docs/auth/admin/manage-users/) also provides profile management features to keep track of signed in users, last sign on etc.                            |
|  <img src="./icons/firestore.png" width="50px" />      |    `Firestore`    |  [Cloud Firestore](https://firebase.google.com/docs/firestore) is a highly scalable NoSQL Database natively integrated in Firebase, it's the easiest way to store 'User generated data' on Firebase. |

<br/>


#### 💵 Payments

|                                                        |        Service       |                  Rationale                                                                                                                                                                                                             |
| ------------------------------------------------------ | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     <img src="./icons/stripe.png" width="500px" />      | `Stripe Firebase SDK`|  [Stripe Firebase SDK](https://firebase.google.com/products/extensions/stripe-firestore-stripe-payments) enables users to sign-up for your digital goods and paid content with Stripe Checkout and manage their subscriptions with the Stripe customer portal. It syncs customers' subscription status with your Cloud Firestore and adds custom claims using Firebase Authentication for convenient access control in your application. |
<br/>


#### 📺 Video Management

|                                                        |                  Service               |                  Rationale                                                                                                                                                                                                          |
| ------------------------------------------------------ | -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="./icons/cloud_storage.png" width="50px" />   |         `Google Cloud Storage`         |  [Google Cloud Storage](https://cloud.google.com/storage/docs) is Google Clouds' petabyte scale Blob Storage offering. It has a 99.95% availability SLA, it is highly scalable, it is supporrted by most Mobile App development tools including Exo player, Firebase and Flutter. |
|   <img src="./icons/firestore.png" width="50px" />     |            `Cloud Firestore`           |  [Cloud Firestore](https://docs.microsoft.com/en-us/azure/data-factory/) is also ideal for storing Video metadata.  |
| <img src="./icons/cloud_functions.png" width="50px" /> |     `Cloud Functions for Firebase`     |  [Cloud Functions for Firebase](https://firebase.google.com/docs/functions)  is a serverless framework that lets you automatically run backend code in response to events triggered by Firebase features and HTTPS requests. It's ideal for video preprocessing, thumbnail extraction, video compression etc. |

<br/>


#### 👀 Admin Dashboard

|                                                        |         Service         |                  Rationale                                                                                                                                                                                                           |
| ------------------------------------------------------ | ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/cloud_storage.png" width="50px" />  |  `Google Cloud Storage` |  [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/) is Azure's cloud ETL service for scale-out serverless data integration and data transformation.                                              |
|    <img src="./icons/firestore.png" width="50px" />    |        `Firestore`      |  [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/) is Azure's cloud ETL service for scale-out serverless data integration and data transformation.                                                            |


