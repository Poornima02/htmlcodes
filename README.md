# htmlcodes
<!DOCTYPE html>
<html>
<head>
<title> Customer Overview</title>
<style>
    table, th, td{
        border:1px solid white;
        border-collapse: collapse;
    }
</style>
</head>
<body style="background: black;color: blanchedalmond;">
<div style="float: right;">
    <label for="search">Search by</label>
    <select id="search" name="search" value="Cust Name">   
    </select>
    <input type="text" id="searchbytext" name="searchbytext" value="Search text here..">
    </br></br>
</div>

<table style="width:100%;">
<tr style="padding: 1px;background-color: blanchedalmond;color: black;">
    <th>
        <input type="checkbox">
    </th>
    <th>Cust Code</th>
    <th>Customer Name</th>
    <th>Address</th>
    <th>City</th>
    <th>Country</th>
    <th>Email</th>
    <th>Status</th>
    <th>Contact</th>
    <th>Payment Terms</th>
    <th>Credit Limit</th>
    <th>Created By</th>
    <th>Created Dt</th>
</tr>
<tr>
    <td>
        <input type="checkbox" >
    </td>
    <td>A0304</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>Active</td>
    <td></td>
    <td>0</td>
    <td>0.00</td>
    <td>Admin</td>
    <td>23/08/2020</td>
</tr>
<tr>
    <td>
        <input type="checkbox" value="selected">
    </td>
    <td>A1001</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>Active</td>
    <td></td>
    <td>0</td>
    <td>0.00</td>
    <td>Admin</td>
    <td>23/08/2020</td>
</tr>
</table>
</body>
</html>
