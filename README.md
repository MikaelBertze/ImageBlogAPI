# ImageBlogAPI
REST API for my image blogs.


HTTP Method     | Action                                 | Example                                              |
----------------|----------------------------------------|------------------------------------------------------|
GET             |Get all image descriptors for 2015      | http://hostname/api/images/year/2014                 |
GET             |Get all image descriptors for march 2015| http://hostname/api/images/year/2105/month/3         |
GET             |Get all image descriptors for 2015-03-10| http://hostname/api/images/year/2105/month/3/day/10  |
GET             |Get image with id = 101                 | http://hostname/api/images/id/101                    |
