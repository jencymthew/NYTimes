# NYTimes
Build a simple App by using Most popular Artilcles API.
Period used as 7.
Here, I used Android Studio2.3.2 and compile the Volley Library for reading HTTPs and Parsing Json Data.
Android Support Design and support have used for RecyclerView and UI designs.
NYTimesMostPopular app have two main Class i.e;MainActivity and Design Activity.
The SubPackages are 'ADAPTER' which contians RecyclerView Adapter named as "RVAdapter",'COMMON' which contains "Const" class inserted the Base url,'DATA' which contains the object class.
And MainActivity contain the "most Popular" Layout and the Json parsing sections.
The Adapter contains the rv_item layout.
The detailsActivity contains"detail" layout, which will show the 'abstrct' section of the API.
The Test can be done by debugg and "Record Espresso Test" done. 

For coverage report I have to insert the code  debug {
            testCoverageEnabled true
        }
and 
jacoco {
                version = '0.7.9'
            }
            this code also in gradile.
            


