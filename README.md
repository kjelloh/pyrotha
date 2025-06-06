# pyrotha
The seed for a core design of peer-to-peer distributed interplanetary immutable Tha data model for emergent human interaction and coexistence.

Also see ['cpptha'(https://github.com/kjelloh/cpptha)] for an attempt to define a C++ meta language based on the 'Tha' type system data model idea.

The namne if a word play on the greek word 'phyros' menaing 'fire' and 'Tha' which the the working name of the four meta tier data model eluded to in YouTube playlist ['C++ Tha Tha'](https://www.youtube.com/watch?v=zdF_evtjJGg&list=PLl2MXgNWEbwE34Cxjx9uW-wdq7RyZ_uQj).

# The PyroTha four meta tier design

The PyroTha model four meta-tiers. Each tier model objetcs that act as constructors for objects on the meta-tier below it.

The seed for the PyroTha four tier data model comes from programming languages type systems. These types systems uses 'variables' as the actual things that holds IRL (run time) values. These values are categorised into 'types'.

From the 'Variable' <-> 'Type' relation we get the two bottom tiers of the PyroTha data model.

* Meta tier 0: 'Variables' (IRL values)
* Meta tier 1: 'Types' (Platonic 'sets' of possible values for each type)

From type systems we can further identify 'type constructors'. These can be seen as objects on meta tier 2. In the PyroTha data model they are further identified to actually be restricted to data structure topology in that these includes construct 'PRODUCT' and 'SUM' types. By also adding the type constructor that specialize or extends and existing data structure we get the three meta tier 2 objects of the PyroTech data model.

* Meta tier 2: 'Composites' (E.g., PRODUCT and SUM type composite plus 'SPECILIZED' composite)

In languages like C++ we are further able to create 'templates' that in PyroTech is identified as objects on meta tier 3 that creates 'type composite constructors'. In computer science these are also called 'generics' in that they are used to take values, types or type constructors as arguments to create value, type or type constructor objects.

* Meta tier 3: 'Generics' (E.g. C++ templates, 'functions' that take meta tier objects as arguments and creates constructors for meta tier objects)

# The PyroTha data model design whish list

## The PyroTha data model core design shold be programming language agnostic 
 
The seed for the 'Tha' data model in youtube playlist above uses the C++ programming language to flesh out Tha data model aspects. But 'PyroTha' aims to be programming language agnostic in that the definition is based on general computrer science concepts ad data types.

## The PyroTha data model representatio should be implementation agnostic

The aim of PyroTha data model is that it should be representable in a variety of existing file formats like JSON, XML, YAML and what have you.
