# Unexpected Behavior When Modifying Instance Variable Through Getter Method in Ruby

This example demonstrates a common, yet subtle, error in Ruby when attempting to modify an instance variable (@value) through its getter method (value).  In Ruby, getter methods typically only return the value; they don't provide a mechanism for setting the value.  Attempting to assign a new value through the getter has no effect on the instance variable.