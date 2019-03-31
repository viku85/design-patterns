# Single Responsibility Principle (SRP)

This is one of the easiest and important principles of all.

The idea is to split in the smallest unit of a group of code. By using this simple principle we can achieve a lot.

This can be extended at a higher level not just by restricting at a function level. Ex in ascending order.

- **Function**: Split codes in smallest unit wrapped in a function.
- **Class**: Group similar functionalities in class. This would be a container of members including functions having a small unit of codes to achieve single goal.
- **Namespace/Folder/Library**: Similar to class the group of classes should be grouped in **namespaces/folder/library**.

More of all this leads to its definition

>Implementation should have only one reason to change. It should not do something as combined, do this and that. Also it should do whatever is in the context to achieve single/common goal.

## Advantages

By splitting into the smaller unit we get various advantages some of are as follows:

- If a function needs any modification, Developer would know what is expected behaviors of the function since it would easier to understand no matter who wrote the code.
- If the application uses Unit tests, the code coverage could be much higher, meaning different result can be expected just by going through it without overthinking of what results may due to a small unit of codes.
- If codes are grouped together, it is much easier to find responsible codes in big projects, in case of any issue arises.

With SRP, if we include **Do Not Repeat Yourself (DRY)** Principle, it is going to be a formidable force for maintaining quality and manageability.

DRY again is very simple, which states whatever you write a group of code do not write/repeat those again. Reuse as much as you can.

So, if we break our codes in small units and re-use, we do not have to worry about managing things at a large extent.