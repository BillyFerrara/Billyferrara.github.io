---
layout: post
title:      "Scope Rules for Local Variables"
date:       2020-07-12 15:33:59 +0000
permalink:  scope_rules_for_local_variables
---


Understanding scope when learning to program is essential. Without understanding the scope of a variable our code would be full of errors and would most likely never get off the ground! Global variables, Class variables, Local variables and Instance variables all have there own purpose and reach. This reach is what we call scope. 

Local variables are one of the most common types of variables we'll encounter when coding. They are an incredibly useful (and necessary!) tool we can use when storing/organizing data so that we can access/use it. Unlike Global or Class variables, Local variables are only accessible within the block it was create in. For example if we declare a variable a = 55 then have a seperate block of code underneath it also defining a = 100, when we run our code the a =100 variable in the block is going to take precident. This is because the a = 55 does not fall under the scope of our block but the a = 100 is encapsulated within our block making it a local variable. 
