# Website Iron Depot

## Synopsis
This website uses a springboot framework and React on the front end. It is used to deiplay a website calling a nonsql database and it is stored on a local server. 

## Motivation
My motivation for building this was the fact that thw store I shop at, Iron Depot, did not have a website and i wanted to get them started with one to make their public reach a little better. 
## How to Run
The files needed to run this are attached, but one of the files was too big to be uploaded. Please reach out to me to luish1999pere@gmail.com for the remaining files. 
## Code Example
I am prode of this next piece of code because it allowes me to circle back into the data base and it displays everyting into cards until the database has run out of objects. 
```
 const [products, setProducts] = useState([]);
    useEffect(() => {
        loadProducts();
    }, []);
    const loadProducts = async () => {
        const request = await axios.get("http://localhost:8080/api/v1/items");
        setProducts(request.data);
    }
```


## Contributors
Here is a list of thinsg i used to get me throught the project, i woudl recomend checking them out! 
- bootstrap
- springboot initializer
- https://www.youtube.com/watch?v=5PdEmeopJVQ&list=WL&index=2&t=3207s


