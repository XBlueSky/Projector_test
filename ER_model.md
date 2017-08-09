# Entity-Relationship Diagram  

An ER model describes inter-related things of interest in a specific domain of knowledge.  
And it's composed of entity types and specifies relationships that can exist between instances of those entity types.  

[![entity-relationship-diagram](https://github.com/XBlueSky/Projector_test/blob/master/entity-relationship-diagram.png?raw=true)](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model)
## Table of Contents  
  
- [Entity](#entity)  
- [Relationship](#relationship)  
- [Attribute](#attribute)  
  
## Entity  
An entity is a thing that exists either physically or logically.  

####  Entity Set 
``` collection of similar types of entities ```  
####  Entity Type 
``` a category. An entity, strictly speaking, is an instance of a given entity-type ```  
####  Instance
``` a real object in a given entity type ```  
  
  ![entity](https://github.com/XBlueSky/Projector_test/blob/master/entities.png)  
  *Entities are represented by means of rectangles.*  
  
#### Weak Entity  
``` an entity can't live without another entity```   

*represented by means of Double rectangle.*  
  
--- 

## Relationship  
The association among entities is called a relationship.  

*represented by diamond-shaped box*  

### ``` One-to-one ```  
![One-to-one](https://github.com/XBlueSky/Projector_test/blob/master/er_relation_one_to_one.png)  
### ``` One-to-many ```  
![One-to-many](https://github.com/XBlueSky/Projector_test/blob/master/er_relation_one_to_many.png)  
### ``` Many-to-one ```  
![Many-to-one](https://github.com/XBlueSky/Projector_test/blob/master/er_relation_many_to_one.png)  
### ``` Many-to-many ```  
![Many-to-many](https://github.com/XBlueSky/Projector_test/blob/master/er_relation_many_to_many.png)  
  
  ---  
    
## Attribute  
Attributes are the properties of entities.  

![Attributes](https://github.com/XBlueSky/Projector_test/blob/master/er_attributes.png) 
*represented by means of ellipses.*  
  
### ``` Key Attribute  ```   
Key Attribute can only identifies an entity in an entity set.

### ``` Composite Attribute ```   
Composite attributes are made of more than one simple attribute.  

![Composite Attribute](https://github.com/XBlueSky/Projector_test/blob/master/er_attributes_composite.png)  
### ``` Derived attribute ```  
Derived attributes are the attributes that do not exist in the physical database, 
but their values are derived from other attributes present in the database.  

![Derived attributey](https://github.com/XBlueSky/Projector_test/blob/master/er_attributes_derived.png)  
### ``` Multi-value attribute ```  
Multi-value attributes may contain more than one values.  

![Multi-value attribute](https://github.com/XBlueSky/Projector_test/blob/master/er_attributes_multivalued.png)  

