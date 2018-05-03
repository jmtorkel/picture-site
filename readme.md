# wordpress picture site

## setup

copy `.env.sample` to `.env` and add desired values.

## run

`docker-compose up`

website: http://localhost:80
phpmyadin: http://localhost:8080

## todo

- seed wordpress with credentials via docker-compose and .env file.. no registration/setup page
- sitemap
- nice theme
- add icon to gallery post type
- js includes
- page titles
- add a snailtrail under the title on gallery pages
- seo stuff

### design

- home and category pages should have thumbs from each gallery in content area with gallery name, like https://www.nikkla.com/
- list of galleries on left, with about page further down, similar to https://www.levonbiss.com/
- gallery page
    - columnar layout, image with caption beneath