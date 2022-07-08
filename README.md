# Clothes-Rental-Website
Repository to contain all the files including the revision history of the clothes rental portal website.

<h1>Description:</h1>
Is buying costly clothes for a single day occasion seems to be a costly fair?
This project exactly aims to provide value to the customer in this regard. Now, using our application, the user can rent the clothes for a single day during the occasion and return back once it got over. Don't worry we won't do a "Padayappa Rajini" and will keep this as a secret. :P
<br><br/>
<table>
  <tr>
    <th>
      Endpoint type
    </th>
    <th>
      path
    </th>
    <th>
      Description
    </th>
  </tr>
  <tr>
    <td>
      get
    </td>
    <td>
      /countries
    </td>
    <td>
      Provides the user with the list of countries deliverable.
    </td>
  </tr>
  <tr>
    <td>
      get
    </td>
    <td>
      /states/search/findByCountryCode?code=${theCountryCode}
    </td>
    <td>
      Provides the user with the list of states for a given country code.
    </td>
  </tr>
  <tr>
    <td>
      get
    </td>
    <td>
      /products/search/findByCategoryId?id=${theCategoryId}
    </td>
    <td>
      Provides the user with the list of products available for a given product category id.
    </td>
  </tr>
  <tr>
    <td>
      post
    </td>
    <td>
      /checkout/purchase
    </td>
    <td>
      Stores the purchase order details in the database and returns the purchase tracking id.
    </td>
  </tr>
</table>

The application is built using the following technologies.
1. Angular 14 (Frontend)
2. Bootstap (Frontend)
3. Spring boot (backend)
4. Rest API (backend)
5. MySQL (Database)

<img width="735" alt="image" src="https://user-images.githubusercontent.com/36566687/178026953-eabe8609-c9de-4cec-a3e4-13ffbb80e9dd.png">
