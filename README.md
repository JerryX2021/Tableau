# Tableau
Tableau to connect data source :open_file_folder:, analyze metadata :clipboard:, build visualisation :bar_chart: and dashboard reporting :chart_with_upwards_trend:.

In this project, I use data ("Global Library Data") downloaded from Tableau_eLearning platform to find insights of libraries around the world. I use both Tableau Desktop to analyze the data and build dashboard. This is also performed using Tableau Online to aid easier information sharing and discussion.\
The Tableau workbook "Global Library Data Dashboard.twbx" is attached. The "raw_data" folder contains the Microsoft Excel worksheet.

The end user can open the ".twbx" file using Tableau Desktop or Tableau Online to interactively view the dashboard, and find information of interest.\
For example, we can select the "Europe" bar from the top chart to only view European library data, where the bottom chart also reflects to this selection. The two charts are filtered by the top chart to enable interactive dashboard.\
We can then :ballot_box_with_check:sort the bottom chart by, for example, the :moneybag:"Expenditure" so that we know the United Kingdom tops the list by spending more than :dollar:USD$4.5 billion on libraries, followed by Germany and France each spends :dollar:USD$2.7 billion and :dollar:USD$1.8 billion on libraries.

![image](https://user-images.githubusercontent.com/76986018/147400882-61230642-5454-4d2e-aefa-776558793b58.png)

We :ballot_box_with_check:sort the bottom chart by the :octocat:"Total Users" and find Russia has the most library users (60 million) in Europe followed by UK and Italy. This is an interesting finding as Russia is not in the top :keycap_ten: "Expenditure" countries in Europe.

![image](https://user-images.githubusercontent.com/76986018/147401059-3943a483-f8a1-4989-85fe-0c0e9aa607cc.png)

We :ballot_box_with_check:sort the bottom chart by the :books:"Total Volumes" and find Germany tops the list with more than 3.7 billion :books:volumes of books in its libraries. That's a massive number of books!:star:

![image](https://user-images.githubusercontent.com/76986018/147401209-7399555e-5603-4138-8490-f1da900999d3.png)

What can we understand from the library data so far:question:

The top library :moneybag:spending countries in Europe are possibly a reflection of the current economic status. It may also show the :dollar:cost of running a library for each country.\
For example, the United Kingdom:uk: spends 60% more on :moneybag:expenditure than Germany:de:, though the United Kingdom:uk: operates 30% less :post_office:libraries than Germany:de:. Does that mean the library expenditure in UK:uk: is less efficiently used that its counterpart? Not necessarily true. The :octocat:"Total Users" of UK:uk: libraries are more than three times that of Germany:de:, giving the actual expenditure per user in UK:uk: less than that in Germany:de:. We look further at the :books:"Total Volumes" of UK:uk: and Germany:de: and notice Germany:de: has almost ten times total volumes compared to its counterpart, despite its less :moneybag:expenditure than UK's. This is interesting. It probably shows the library :moneybag:expenditure mainly contributes to serving library :octocat:users, rather than storaging the :books:volumes. Fair enough!

Russian:ru: libraries stores the second largest :books:volume of books (1.9 billion) in Europe and serves the largest library :octocat:users (60 billion!) in Europe, using a total expenditure of :dollar:USD$53 million. This is a reflection of the economic status in the country, such as the :guardsman:manpower cost to operate and maintain libaries.

What if we include library data from all countries:question:

We de-select the previously used filter so all :earth_americas:country data are included.\
:ballot_box_with_check:Sort the bottom chart by :moneybag:"Expenditure". Wow:exclamation: The United States:us: spends more the :dollar:USD$21 billion to run its 101,349 :post_office:libaries. That's :five: times of :dollar: spends by the UK.

![image](https://user-images.githubusercontent.com/76986018/147401809-3df69b29-093d-4dfb-a883-77e809936551.png)

:ballot_box_with_check:Sort the bottom chart by :post_office:"Total Libraries". India tops the list by having 337,020 libaries countrywide, followed by Indonesia (122,906), Russia (113,867), China (109,673) and the US (101,349). This is reasonable as all countries have a :smirk_cat:population of over 200 million.

![image](https://user-images.githubusercontent.com/76986018/147401997-83080966-ae7a-492b-a5dc-98871e8afa89.png)

:ballot_box_with_check:Sort the bottom chart by :octocat:"Total Users". Wow:exclamation: South Korea:kr: tops the list with more than 438 million library :octocat:users, almost double the number of library users of the runner up, the United States:us:. Moreover, South Korea:kr: spends less than 5% of US :moneybag:expenditures with a budget of :dollar:USD$1.2 billion. This is an impressive achievement.:star:

![image](https://user-images.githubusercontent.com/76986018/147402036-f50cda3c-1555-40c0-8c67-d16a9a533bdc.png)

:ballot_box_with_check:Sort the botom chart by :books:"Total Volumes". Germany:de: still tops the rank and must have made great efforts to preserve and archive books. United States:us: comes the second, followed by Russia:ru:, Japan:jp: and China:cn:. Each of the top :five: "Total Volume" countries has more than 1 billion total :books:volume of books.

![image](https://user-images.githubusercontent.com/76986018/147402096-771e14a8-d63f-4348-838a-7e3b55f17ad9.png)

:books::books::books:Knowledge is priceless.Running a :post_office:library has a :moneybag:price tag.

The library :moneybag:expenditure may reflect the :chart_with_upwards_trend:economic status of countries, it does not necessarily reflect the :octocat:usage of librairies and it is not a reflection of :books:knowledge gained in population.:star::star::star:

This :page_with_curl:project shows how we can use Tableau Dashboard to :repeat:interactively analyze and report data :bar_chart:.

