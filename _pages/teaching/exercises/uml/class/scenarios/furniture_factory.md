---
layout: page
title: Furniture Factory
include_in_menu: false
permalink: /teaching/exercises/uml/class/scenarios/furniture_factory/
crumbtitle: Furniture Factory
tags: exercises uml
---

## Furniture Factory

The known furniture factory Hi-Key-Ah, intends to implement an information system to store all data on the different types of furniture and components it produces:

- The factory produces several lines of furniture, each with a different name and consisting of several pieces of furniture of different types (beds, tables, chairs, …).
- All furniture pieces have a type, a single reference (eg CC6578) and a selling price.
- The major competitive advantage of this innovative plant is the fact that each component produced can be used in more than one piece of furniture.
- Each piece of furniture is thus composed of several components. The same component can be used more than once in the same piece.
- Every type of component produced is assigned a unique numerical code, a manufacturing price and a type (screw, hinge, shelf …).
- The furniture is then sold in various stores throughout the world. Each store has a different address and a fax number.
- To make the manufacturing process more efficient, stores have to place orders everytime they need to replenish their stock. These orders must also be stored in the database.
- Each order has a order number, a date, the store that placed the order as well as a list of all the ordered furniture and their quantities.


### Acknowledgement

Credits: [André Restivo](https://web.fe.up.pt/~arestivo/page/exercises/entity-relationship/furniture/)
