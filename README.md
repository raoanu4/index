# index
something....
function ActiveLink(){
  function HandleClick(e){
    e.preventDefault();
    console.log("the link was clicked");
  }
  return(
  <a href="#" onClick={HandleClick}>Click Me</a>
  );
}

ReactDOM.render(
<ActiveLink/>,
  document.getElementById('root')
);
