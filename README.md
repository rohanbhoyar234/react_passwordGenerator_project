This is a Random Password Generator Project.
Here I used the React Library of JavaScript. 

About the project :
    This project provides the user with minimun of 6 character and maximum of 16 character password , according to the range choosen.
    It provides the user the option of whether they want the numbers or special character in their password or not.
    Then simply by clicking on copy button, the password get copy to the clipboard.


The hooks that I used in this project are :

    useState() : 
     #   to import use:  import { useState } from 'react';
     useState() Hook lets us add a state variable to yur component. The useState() hook can conveniently hold strings, arrays, numbers, objects and much more.

    useCallback() :
      #   to import use:  import { useCallback } from 'react';
      useCallback() allows us to isolate resource intensive functions so that they will not automatically run on every render.
      The useCallback Hook only runs when one of its dependencies update.

    useEffect() :
    #    to import use:  import { useEffect } from 'react';
    The useEffect Hook allows us to perform side effects in our components.
    useEffect accepts two arguments. The second argument is optional.
    useEffect(<function>, <dependency>)

    useRef() :
    #  to import use:  import { useRef } from 'react';
    The useRef Hook allows us to persist values between renders.
    It can be used to store a mutable value that does not cause a re-render when updated.
    It can be used to access a DOM element directly.

We can import all these hooks in one statement also :
    import {useState , useCallback , useEffect , useRef} from 'react';


Happy Coding...



