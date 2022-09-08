# assignment2-chennu

# Amani Chennu

###### Hyderabad museum is my favourite place 

There are many spots in that museum where we can find most **interest facts** about the city. 

we can see the **potraits** of the __kings__ who ruled this city in the __early times__. we can also find the things used by them.

---
# Specifing the airport 

The nearest airport for the museum is Rajiv Gandhi International aiport.<br>
After coming out from the airport, there will be cabs available. we can book a cab <br>
They will drop you at the museum. It is just a 20 minutes travel time for us to go to the museum.

*   Restaurant
*   Park
*   Shopping mall

***[AboutMe.md](./AboutMe.md)***

***

# Reccomendation of cities
This table is about the cities and the locations to visit in the cities.The travelling time also mentioned in the table to give an idea about it.

|  City    | Location   | Time Spending |
|   ---    |  ---       |  ---    |
|Vizag     | Araku      | 24 Hrs  |
|Thirupathi|Temple      |  48 Hrs |
|Vijayawada|River Krishna|  24 Hrs|
|Eluru     |Valley       |  30 Hrs|

***

# Quotes 
> "A Perfect sister i am not, but thankful for the one I've got.."

*John D*

>"Nothing is permanent, Everything will change"

*Bushra Ashraf.*

***

# Code Fencing
> What is SaaS, PaaS and IaaS? With examples
><https://stackoverflow.com/questions/16820336/what-is-saas-paas-and-iaas-with-examples>


```
@mixin stripes($direction, $colors) {
  $length: length($colors);
  
  @if $length > 1 {
    $stripes: ();
    
    @for $i from 1 through $length {
      $stripe: (100% / $length) * ($i - 1);
      
      @if $i > 1 {
        $stripes: append($stripes, nth($colors, $i - 1) $stripe, comma);
      }
      
      $stripes: append($stripes, nth($colors, $i) $stripe, comma);
    }
    
    background-image: linear-gradient($direction, $stripes);
  } @else if $length == 1 {
    background-color: $colors;
  }
  
  ```
  > snippet source link
  ><https://css-tricks.com/snippets/sass/striped-gradient-mixin/>