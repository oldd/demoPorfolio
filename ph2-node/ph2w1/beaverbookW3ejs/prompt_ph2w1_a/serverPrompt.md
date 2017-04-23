import modules

configure server

static serving
	any resources that do not change as the data changes 
	(style, scripts, HTML ...)

Beaver handlers  
|  HTTP method  |  URL | Behavior  |  
|------------- |---------- |--------- |  
|  GET  | /home | retrieves beavers, renders home EJS |
| GET |  /profile/:id  | retrieves said beaver, renders profile EJS  |  
| POST | /profile/:id/update |  updates said beaver, renders profile EJS | 
| POST | /signup  | creates beaver, renders said profile   |  

start server
