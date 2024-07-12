
## Setup Instructions

1. Create a new app within the existing project:
2. Add 'app2' to INSTALLED_APPS in `myproject/settings.py`.

3. Create templates directory for app2:
4. Create an HTML file for app2:
5. Edit `app2/templates/app2/home.html` with content and links to app1 pages.

6. Create a view in `app2/views.py`.

7. Create URL patterns for app2:
8.  Edit `app2/urls.py` with URL patterns.

9. Include app2's URLs in the project's main URLs. Edit `myproject/urls.py`.

10. Update the URL patterns in `myapp/urls.py` to include names for reverse URL matching.

11. (Optional) Update the HTML files in the first app to include links back to app2.

12. Run the development server:
 ```
 python3 manage.py runserver
 ```

Now access  pages at:
- http://127.0.0.1:8000/app2/ (App 2 home page)
- http://127.0.0.1:8000/app1/page1/ (App 1, Page 1)
- http://127.0.0.1:8000/app1/page2/ (App 1, Page 2)
