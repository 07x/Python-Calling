# Python-Calling
Here I Explained that what is call by value and call by reference in python programming languages




# What is Python call By reference -

When You pass a immutable objects like (String, Tuple,value)to  Your function as parameter .Then This Type of calling is known as **Call by value** becasue if You can not able to change the value of this objects


                                      Call By Value

                                      fruits=("apple")

                                      def value(fruits):
                                          del fruits
                                          print("Tuple Deleted")


                                      value(fruits)    
                                      print(fruits)


# What is Python call By reference - 

And if You pass any mutable objects (list,dictinonary) in Your functions. Then this type of calling is known as **call By refrence** because now if you cange your obect value from inside Your function then then it will also be reflected outside the function.


                                        #CaLL By Reference

                                        def ref(list):
                                            list.append(50)
                                            print(list)

                                        list1=[1,2,3,4,5]
                                        ref(list1)

                                        print(list)





