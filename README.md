@PassDatainMVC.Models
@{
ViewBag.Title="Index";
}
<h3> Passing Data Form Controller<h3>
@{
var data=(Record) ViewData["Message"];
}
<h3> Id: @data.Id</h3>
<h3> RecordName:@data.RecordName</h3>
<h3> RecordDetail:@data.RecordDetail</h3>
