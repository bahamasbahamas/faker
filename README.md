# go-faker
## forked from dmgk/faker

this is a fork of https://github.com/dmgk/faker. 

#### How to install
go get 'github.com/bahamasbahamas/faker'

#### Docs
https://github.com/dmgk/faker

#### What's new?
You can set the language to English or German

      faker.SetLanguage("de") //sets language to German
      faker.SetLanguage("en") //sets language to English

You can create first names with gender
 
      faker.Name().FirstNameFemale() //Lola
      faker.Name().FirstNameMale()  //Sven

I deleted the files in /yaml and the cmd/generator.go 
