# Header level 1

## Header level 2

### Header level 3

#### Header level 4

##### Header level 5

###### Header level 6

## How to write Code in Markdown

````sol

```sol
pragma solidity ^0.8.23;
contract Testing{
    uint256 public myUint;
    function setMyUint(uint _myUint) public {
        myUint = _myUint;
    }
}
````

This is **bold** and this is _italic_. This is `code`.
This is bold italic **_italic_** and this is _bold_ italic.

### How to do markdown in Link

---

[Ronnie's Portfolio](https://portfolio-fl2l.vercel.app/)

![Portfolio](https://w7.pngwing.com/pngs/449/539/png-transparent-career-portfolio-artist-s-portfolio-portfolio-miscellaneous-angle-kitchen-thumbnail.png)

## How to Write Solidity Code

> First Declear The `pragma solidity ^0.8.23;` version of solidity you are using.
>
> > Then Declear the contract name like `contract Testing{}`.
> >
> > > Then declear the variable like `uint256 public myUint;`.
> > >
> > > > Then declear the function like `function setMyUint(uint _myUint) public { myUint = _myUint; }`.
> > > >
> > > > > Then declear the function like `function getMyuint() public view(uint256){ myUint;}`.

## How to do listing in Markdown

> Ordered List

1. First
2. Second
3. Third

> Unordered List

- First
- Second
- Third

> Nesting List

1. First
   - First
   - Second
   - Third
     1. First
     2. Second
     3. Third
        - First
        - Second
        - Third

## How to do Table in Markdown

| Name | Email | Address |
| ---- | ----- | ------- |
| Ron  | Ron   | Ron     |
| Ron  | Ron   | Ron     |
| Ron  | Ron   | Ron     |

## How to do CheckList in Markdown

- [x] First
- [ ] Second
- [ ] Third
- [x] Forth
