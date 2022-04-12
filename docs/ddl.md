---
title: Data Definition Language
description: SQL statements that create the SQLite database for the app.
menu: DDL
order: 40
---

```h2
create table opportunity
(
    opportunity_id  UUID         not null,
    created         timestamp    not null,
    description     varchar(255),
    external_key    UUID         not null,
    name            varchar(255) not null,
    needed_skill    varchar(255),
    title           varchar(255),
    organization_id UUID         not null,
    primary key (opportunity_id)
);
create table organization
(
    organization_id UUID         not null,
    about           varchar(255) not null,
    created         timestamp    not null,
    external_key    UUID         not null,
    latitude        double       not null,
    longitude       double       not null,
    mission         varchar(255) not null,
    name            varchar(255) not null,
    owner_id        UUID         not null,
    primary key (organization_id)
);
create table organization_volunteer
(
    organization_id UUID not null,
    user_id         UUID not null,
    primary key (organization_id, user_id)
);
create table user_favorite
(
    user_id         UUID not null,
    organization_id UUID not null,
    primary key (user_id, organization_id)
);
create table user_profile
(
    user_profile_id UUID         not null,
    created         timestamp    not null,
    display_name    varchar(50)  not null,
    email           varchar(255),
    external_key    UUID         not null,
    location        varchar(255),
    name            varchar(255) not null,
    oauth_key       varchar(30)  not null,
    phone_number    varchar(255),
    primary key (user_profile_id)
);
```
[`ddl.sql`](sql/ddl.sql)
