<h1  align="center">JSON Server</h1>

1. Get single company `/companies/1`
2. Get all users of a company `/companies/1/users`
3. Filter companies by name `/companies?name=Microsoft` & `/companies?name=Microsoft&name=Apple`
4. Pagination & Limit `/companies?_page=1&_limit=2`
5. Sorting `/companies?_sort=name&_order=asc`
6. Users age range `/users?age_gte=30` & `/users?age_gte=30&age_lte=40`
7. Full text search `/users?q=Paul`
