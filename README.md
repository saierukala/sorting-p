## Sorting Products
* Sorting Products
* Price High to Low
* Price Low to High
* Installing Third-Party Packages
* react-icons

// npm install --save react-router-dom@5.2.0
// npm install js-cookie --save
// npm install react-icons
// npm install react-loader-spinner@4.0.0 --save
-----------------------------------------------------------------------

// products hearder
//All productsSection
------------------------------------------------------------------------

##  setState() - Callback Function
The setState() is asynchronous, it takes an optional callback parameter that can be used to make updates after the state is changed.

# Syntax

this.setState({property1: value1,...}, callbackFunction)
------------------------------------------------------------------------

## React Icons
react-icons is a third-party package contains bundle of icons like bootstrap, font awesome, material icons etc..,

# Check react-icons website

https://react-icons.github.io/react-icons/
------------------------------------------------------------------------

## Installing React Icons
This below command installs all the react-icons library in your React project.

# npm install react-icons
------------------------------------------------------------------------

## 2.3 Importing React Icons
The First letters of the icon indicates the category of the Icon.

Each category of Icons have import statements separately, go to the category and copy the import statement.

## Example:

import { BsFilterRight } from "react-icons/bs";
import { FaFacebookF } from "react-icons/fa";
import { MdDelete } from "react-icons/md";

const ReactIcon = (props) => {
  return (
    <div>
      <BsFilterRight />
      <FaFacebookF />
      <MdDelete />
    </div>
  );
};

export default ReactIcon;
------------------------------------------------------------------------



