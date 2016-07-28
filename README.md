vk_api_auth
===========

Python module for authorization in vk.com API.

usage: 

	import vk_auth # vk_auth3 as vk_auth  for python3
	token, uid = vk_auth.auth(email, pass, id_app, scope)
	#token - token from vk for you app, uid - id user are authorized.
