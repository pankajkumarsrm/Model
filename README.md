@using usingDatainMVC.Models
@{
ViewBag.Title="Index";
}
<h3> Passing Data Form Controller<h3>
@{
var data=(Record) ViewData["Message"];
}
<h3> Id: @data.Id</h3>
<h3> RecordName:@dataName</h3>
<h3> RecordDetail:@dataDetail</h3>
