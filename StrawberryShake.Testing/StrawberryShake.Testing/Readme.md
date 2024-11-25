Uncomment the graphql in NotWorking.Graphql and attempting to build the project will illustrate the issue

Essentially an errant ">" character is generated when using the Dictionary scalar type as an output field. 
Seems fine when used as input. The Dictionary type itself is declared in the schema.extensions.grapqhl