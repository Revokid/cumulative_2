# cumulative 2
# Back-End Web Development 1 - HTTP-5125-RNA

This project is part of a cumulative assignment to build a Minimum Viable Product (MVP) for managing a school database. The focus is on the Teachers table, using ASP.NET Core Web API and MVC. In Part 2, we implement the functionality to add and delete teachers through both API endpoints and server-rendered web pages.

The final product allows users to perform Create, Read, Update, and Delete (CRUD) operations on the Teachers table with a focus on server-side rendering and API interactions.

# Features
1. Add Teacher: Create new teacher records through an API and a web page.
2. Delete Teacher: Remove existing teacher records using the API or confirmation pages.
3. Validation: Includes server-side checks for required fields and unique constraints.
4. Initiative Features:
   Error handling for invalid inputs (e.g., future hire dates, empty names, duplicate employee numbers).
   Client-side validations and potential AJAX integration.

# API Endpoints
 1. POST /api/TeacherAPI/add
    Adds a new teacher.
 2. DELETE /api/TeacherAPI/delete/{id}
    Deletes an existing teacher by ID.
