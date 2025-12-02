
---

# **Flask Interview Questions – Complete Master List (150 Questions)**

*(Organized by category and difficulty)*

---

# **I. Basics (1–30)**

1. What is Flask?
2. Why is Flask called a micro-framework?
3. What languages does Flask rely on?
4. Who created Flask and when?
5. What is `Werkzeug`?
6. What is `Jinja2`?
7. How do you install Flask?
8. What does `Flask(__name__)` represent?
9. What is a route in Flask?
10. How do you define multiple routes for the same function?
11. What are HTTP methods supported by Flask?
12. What is the default HTTP method if not specified?
13. How do you return JSON data from a route?
14. What is `app.run(debug=True)` used for?
15. What is the difference between development and production servers?
16. How do you use Flask’s built-in server?
17. What is the purpose of `render_template`?
18. Where do templates go in a Flask project?
19. Where do static files go in a Flask project?
20. How do you read query parameters (URL arguments)?
21. How do you read POST form data?
22. What is the `request` object?
23. What is the `session` object?
24. What is the `url_for()` function used for?
25. How do you redirect a user in Flask?
26. What is the purpose of `flash()`?
27. What is the role of `config['SECRET_KEY']`?
28. How do you enable CORS in a Flask application?
29. How do you handle file uploads in Flask?
30. What is the purpose of `abort()`?

---

# **II. Templates & Jinja2 (31–50)**

31. What is template inheritance in Jinja2?
32. What is `{{ }}` used for?
33. What is `{% %}` used for?
34. What are filters in Jinja2?
35. How do you create a custom Jinja2 filter?
36. How do you escape HTML in Jinja2?
37. How do you loop through a list in Jinja2?
38. How do you show conditional blocks in Jinja2?
39. How do you include one template inside another?
40. How do you pass variables into a template?
41. How do you format dates in Jinja2?
42. How do you handle CSRF tokens in templates?
43. What is a macro in Jinja2?
44. How do you load static files in templates?
45. What is the meaning of `{% extends "base.html" %}`?
46. How do you create global template variables?
47. What are context processors?
48. How do you include reusable components?
49. What is white-space control in Jinja2?
50. What is auto-escaping?

---

# **III. Routing, Requests & Responses (51–75)**

51. What is dynamic routing?
52. How do you define type-constrained variables in routes?
53. How do you return a custom HTTP status code?
54. What is `make_response()`?
55. How do you add custom headers?
56. What are before-and-after request handlers?
57. What is `@app.before_request` used for?
58. What is `@app.after_request` used for?
59. What is `@app.teardown_request` used for?
60. What is the difference between request hooks?
61. How do you access cookies?
62. How do you set cookies?
63. What is streaming responses used for?
64. What are large file responses handled with?
65. How do you send files for download?
66. What is a WSGI environment?
67. What is the `g` object used for?
68. What is the application context?
69. What is the request context?
70. What is `local` in Werkzeug?
71. What are MIME types?
72. How do you validate request data?
73. What is `request.is_json`?
74. What is an idempotent request?
75. Why should GET not modify server state?

---

# **IV. Flask Architecture & Blueprints (76–100)**

76. What are Flask Blueprints?
77. Why use Blueprints in large applications?
78. How do you register a Blueprint?
79. How do you create nested Blueprints?
80. What is the application factory pattern?
81. Why use app factories?
82. What is dependency injection in Flask?
83. What is the `extensions` registry pattern?
84. What is modular routing?
85. How do you maintain environment configurations?
86. How do you load config from a Python file?
87. How do you load config from environment variables?
88. How do you load config from a `.env` file?
89. How do you use instance folders?
90. What is the purpose of `__init__.py` in Flask packages?
91. How do you separate API and UI routes?
92. What are Flask CLI commands?
93. How do you create custom CLI commands?
94. What is the Flask application lifecycle?
95. What is the difference between `current_app` and `app`?
96. What is lazy loading in Flask?
97. How do you organize a scalable folder structure?
98. What is a common structure for enterprise Flask apps?
99. What is the difference between single-file and multi-module apps?
100. How do you integrate Flask with a frontend like React or Vue?

---

# **V. Databases & ORM (101–120)**

101. How do you connect to SQL databases?
102. What is SQLAlchemy?
103. What is the Flask-SQLAlchemy extension?
104. What are database models?
105. How do you create tables in SQLAlchemy?
106. What is the role of sessions in SQLAlchemy?
107. What is the difference between `session.commit()` and `session.flush()`?
108. What are SQLAlchemy relationships?
109. Explain one-to-many relationships.
110. Explain many-to-many relationships.
111. What is eager loading?
112. What is lazy loading?
113. How do you perform database migrations?
114. What is Flask-Migrate?
115. How do you handle schema versioning?
116. How do you manage database transactions?
117. How do you handle database exceptions?
118. How do you integrate NoSQL like MongoDB?
119. What is Flask-PyMongo?
120. How do you use Redis with Flask?

---

# **VI. Authentication, Security & Authorization (121–140)**

121. What is session-based authentication?
122. How do you use Flask-Login?
123. How do you implement role-based access control?
124. What is CSRF protection?
125. What is Flask-WTF?
126. How do you secure cookies?
127. How do you use JWT authentication?
128. What is token-based authentication?
129. What are refresh tokens?
130. Why should passwords be hashed?
131. What hashing algorithms does Werkzeug support?
132. What is OAuth2 and how to integrate it?
133. How do you protect against XSS attacks?
134. How do you protect against SQL injection?
135. How do you protect against brute-force attacks?
136. What is Flask-Limiter?
137. What is HTTPS enforcement?
138. How do you implement request throttling?
139. How do you secure sensitive config variables?
140. How do you store secrets safely?

---

# **VII. Async, Performance, Caching, Background Tasks (141–165)**

141. How does Flask handle concurrency?
142. What is the difference between threads and processes in Flask?
143. Is Flask asynchronous? Why/why not?
144. How do you run background tasks?
145. What is Celery and how do you integrate it?
146. What is message queuing and why use it?
147. How do you use Redis queues?
148. How do you implement caching?
149. What is Flask-Caching?
150. How do you avoid N+1 query problems?
151. How do you use profiling tools with Flask?
152. How do you measure API performance?
153. How do you optimize JSON serialization?
154. What is connection pooling?
155. How do you use Gzip compression?
156. How do you paginate responses?
157. How do you stream large responses?
158. How do you benchmark Flask endpoints?
159. How do you add async endpoints in Flask 2.x?
160. When should you use FastAPI instead of Flask?

---

# **VIII. Deployment, DevOps & System Design (166–200)**

166. How do you deploy Flask using Gunicorn?
167. How do you deploy Flask using uWSGI?
168. What is a WSGI file?
169. What is the difference between NGINX and Gunicorn?
170. Why should Flask not be run with the built-in dev server in production?
171. How do you containerize a Flask app using Docker?
172. What does a typical Dockerfile for Flask look like?
173. How do you use docker-compose with Flask?
174. How do you deploy Flask on AWS EC2?
175. How do you deploy Flask on AWS Elastic Beanstalk?
176. How do you deploy Flask on Azure App Services?
177. How do you deploy Flask on Google Cloud Run?
178. How do you configure CI/CD for Flask?
179. How do you manage environment variables in production?
180. What is gunicorn worker class?
181. How do you scale Flask horizontally?
182. How does load balancing work?
183. How do you use Redis as shared session storage?
184. How do you serve static files behind NGINX?
185. How do you configure reverse proxies?
186. What is Zero-Downtime deployment?
187. What is Blue-Green deployment?
188. How do you implement health checks?
189. How do you monitor Flask apps?
190. What logging strategies should you use in production?
191. How do you integrate Sentry with Flask?
192. How do you add rate limiting in production?
193. How do you integrate API gateways?
194. How do you protect APIs behind firewalls?
195. How do you secure Flask deployment at network level?
196. How do you handle distributed caching?
197. How do you store user uploads safely?
198. How do you build a multi-tenant Flask app?
199. How do you architect a microservices system using Flask?
200. When is Flask not a suitable choice?

---



