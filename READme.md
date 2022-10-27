Describe: americanExpress();
Test: "Has a mininum of 15 digits and a maximum of 16 and starts with either 34 or 37." 
Code: const text = "341098657452854"
creditCard();
Expected Output: ""This card number is valid.""

Describe: visaCard();
Test: "Has a mininum of 16 digits and a maximum of 17 and starts with 4." 
Code: const text = "4109865745288544"
creditCard();
Expected Output: ""This card number is valid.""

Describe: masterCard();
Test: "Has a mininum of 16 digits and a maximum of 17 and starts with 5." 
Code: const text = "5109865745288544"
creditCard();
Expected Output: ""This card number is valid.""

Describe: discoverCard();
Test: "Has a mininum of 16 digits and a maximum of 17 and starts with 6." 
Code: const text = "6109865745288544"
creditCard();
Expected Output: ""This card number is valid.""