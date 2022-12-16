function popupku() {
  var body = document.querySelector("body");      
  var pWm = document.createElement("a");
  pWm.setAttribute("href", "fikriprasetiyo");
  pWm.setAttribute("style", "text-decoration: none; color: white; opacity: .5; position: fixed; bottom : 10px; left: 10px");
  pWm.innerHTML = "Fikriprasetiyo";
  body.appendChild(pWm);
}
