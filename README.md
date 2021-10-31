BackEnd: https://github.com/MaddyKilmurray/AdoptAPet

FrontEnd: https://github.com/MaddyKilmurray/adoptapetFron


## BackEnd 

### Setup

Clone/download the repo from this site:

To run this project locally do the following after cloning or downloading the project:

<ol>
  <li> Open the project on your IDE such as IntelliJ </li>
  <li> Go to DiscoveryService folder and run main method </li>
  <li> Go to AnimalService folder and run main method </li>
  <li> Go to AdopterService folder and run main method </li>
  <li> Go to AdoptingService folder and run main method </li>

</ol>

## API documentation:

On http://localhost:8761/
there should be 6 instances registered with Eureka: 
<ul>
    <li>ANIMAL-SERVICE </li>
    <li>ADOPTER-SERVICE</li>
    <li>ADOPTING-SERVICE</li>
</ul>



### Routes:
These are the routes you can try:

On http://localhost:8820/:
<ul>
<li> Method: GET -- Route: animal -- Response: Get all animals </li>
<li> Method: GET -- Route: animal/{id} -- Response: Get an animal by id </li>

</ul>

On http://localhost:8840/:
<ul>
<li> Method: GET -- Route: adopter -- Response: Get all adopters </li>
<li> Method: POST -- Route: adopter/{id} -- Response: Add a new adopter </li>
 <li> Method: GET -- Route: adopter/populate -- Response: Add sample data </li>
</ul>

On http://localhost:8600/:
<ul>
<li> Method: GET -- Route: adopt?startAge=XX&endAge=XX&type=XX -- Response: Get pet by age range and type </li>
<li> Method: POST -- Route: adopt/{id} -- Response: Adopt a pet by id </li>
</ul>
