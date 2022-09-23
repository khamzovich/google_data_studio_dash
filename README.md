# google_data_studio_dash
Example of two-pages dashboard in Google Data Studio

* Random dataset created with Python in Google Colab using pandas, numpy, random, gspread libraries
* Python script automatically saves Dataset to Google Sheets
* Google Sheets is connected to Google Data Studio

**Dataset description**
Visitors sales products (Furniture, Decoration, Lighting) to customers. Visitor shows presentations with slides to customers. We collect information about visit data, duration, attitude to slides etc.

Sheet1 columns:
- call_id: visit id
- date: date of visit
- visitor: visitor name
- visit: type of visit (submitted or canceled)
- city: visitor's sity
- product: type of product Furniture, Decoration or Lighting
- customer: customer name
- plan: planned or not planned visit
- base: type of base (Assigned base, Active base, Non-active base)
- duration: duration of visit

Sheet2 columns:
- call_id: visit id
- date: date of visit
- visitor: visitor name
- visit: type of visit (submitted or canceled)
- city: visitor's sity
- product: type of product Furniture, Decoration or Lighting
- customer: customer name
- plan: planned or not planned visit
- base: type of base (Assigned base, Active base, Non-active base)
- presentation: name of presentation
- slides: name of slide
- url: product image url
- duration_sec: duration of visit
- like: attitude (1 - like, 0 - no reaction)
- dislike: attitude (1 - dislike, 0 - no reaction)

Sheet3 columns:
- visitor: visitor name
- Active base: number of visits from Active Base
- Assigned base: number of visits from Assigned Base
- Non-active: number of visits from Non-active Base
- base: type of base (Assigned base, Active base, Non-active base)
- one_visit: number of customers with one visit
- two_visits: number of customers with two or more visits
- city: visitor's sity
- product: type of product Furniture, Decoration or Lighting

[Google Data Studio dashboard](https://datastudio.google.com/s/sXa_msaiDgk)

First page
![Image](https://github.com/khamzovich/google_data_studio_dash/raw/main/images/first_page.png)

Second page
![Image](https://github.com/khamzovich/google_data_studio_dash/raw/main/images/second_page.png)
