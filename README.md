# Installation

## 1. Download

When you have php7.x installed on your computer:

```
$ curl https://raw.githubusercontent.com/rouffj/snippets-core/master/maker-php7.x.phar -o /tmp/maker
```

When you have php8.x installed on your computer:

```
$ curl https://raw.githubusercontent.com/rouffj/snippets-core/master/maker-php8.x.phar -o /tmp/maker
```

## 2. Make it accessible in your PATH

```
$ chmod +x /tmp/maker
$ mv /tmp/maker /usr/local/bin/
$ git clone https://github.com/rouffj/snippets-core.git ~/snippets-core
```

## 3. Use it

```
$ maker make
➜  maker git:(master) ✗ maker make

 Snippet to execute?:
  [0 ] php:getters
  [1 ] php:unit_test
  [2 ] sf:validator
  [3 ] sf:twig_theme
  [4 ] sf:annotation
  [5 ] sf:form
  [6 ] sf:construct
  [7 ] sf:event_custom
  [8 ] sf:event_symfony
  [9 ] sf:event_doctrine
  [10] sf:security_auth
  [11] sf:security_passwordless
  [12] sf:security_accountchecker
  [13] sf:action
  [14] sf:action_advanced
  [15] sf:console_app
  ...
```

---

You want to create and use your own snippets for your project?

$ maker make -m

 Snippet to execute?:
  [0] my_project:my_snippet
