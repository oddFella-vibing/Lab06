1.  res.render(view, data) compiles an EJS template into HTML(view) by injecting the provided data and sends that HTML as the response to the client.
2.  <%= %> Escaped output as template and <%- %> unescaped output as raw html
3.  Where does Express look for EJS templates (folder path)? /views by default
    app.set("views", path.join(\_\_dirname, "..", "views"));

682115502 AUNG HLAING PHYO
