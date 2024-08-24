# Intl Phone Number Input

A simple and customizable Blazor input for phone numbers.

![image](https://github.com/user-attachments/assets/cbafb4f8-0d8f-4bc4-9455-4f5dc2990f9b)
 
### Features

  - Flag images and dial codes for each country
  
    
## Getting Started (Using a CDN)
1. Add the CSS
  ```html
  <link href="css/international-telephone-input.css" rel="stylesheet" />
  ```

2. Copy over the images
   
3. Copy the component to your project
4. Add the markup to your page and wire up the events as needed

  ```html
  
<div class="mb-3">
    <InternationalPhoneNumber Id="InternationalPhone1" Class="form-control" @bind-BindingValue="_internationalPhone"></InternationalPhoneNumber>
</div>
@code{

    private string _internationalPhone = "";

}
  ```
   
   
  
