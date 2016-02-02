FullCalendar-Ajax-Php-Mysql
===========================

FullCalendar with insert, add, edit and delete options (Ajax/PHP/Mysql)

FullCalendar is a jQuery plugin that provides a full-sized, drag & drop calendar. It uses AJAX to fetch events on-the-fly for each month and is easily configured to use your own feed format (an extension is provided for Google Calendar). It is visually customizable and exposes hooks for user-triggered events (like clicking or dragging an event). It is open source licensed under an MIT license.

Install PHP, MySQL. Then run following mysql commands:


mysql> create database fullcalendar;

mysql> use calendar;

mysql> CREATE TABLE events (id INT NOT NULL PRIMARY KEY AUTO_INCREMENT, 
title VARCHAR(100),
start DATE,
end DATE);

Source code taken from https://github.com/cturpin/FullCalendar-Ajax-Php-Mysql and changed.

Used http://fullcalendar.io/ fullcalendar javascript library.
