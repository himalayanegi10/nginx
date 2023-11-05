# Nginx-Opensource
### Overview
> Nginx is a high performance web server. Nginx acts as a "Reverse Proxy" between internet and application servers. Nginx does "Load Balancing" while acting as a reverse proxy. Nginx also does Encrpytion/Decription of messages.
### Terminologies
#### Directives
> A key value pair in a nginx.conf file is called a directive. Example 

`root /usr/local/.../mysite;`
#### Context
> A context is a code block which contains one or more directives. Example

```
location site/ {
    root /usr/local/.../mysite;
}
```