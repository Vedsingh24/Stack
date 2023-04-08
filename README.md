# Stack is a data structure which has a first in last out configuration. It has a top where insertion and deletion occurs. Stack has many applications some of which are: Backtracking, Memory management and evaluating expressions. Algorithm for a stack using arrays is:
1.begin procedure peek
   return stack[top]
end procedure
2.begin procedure isfull

   if top equals to MAXSIZE
      return true
   else
      return false
   endif
   
end procedure
3.begin procedure isempty

   if top less than 1
      return true
   else
      return false
   endif
   
end procedure
4.begin procedure push: stack, data

   if stack is full
      return null
   endif
   
   top ← top + 1
   stack[top] ← data

end procedure
5.begin procedure pop: stack

   if stack is empty
      return null
   endif
   
   data ← stack[top]
   top ← top - 1
   return data

end procedure
