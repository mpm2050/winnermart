---
title: "Admin"
date: 2019-10-17T11:22:16+06:00
draft: false
description : "this is a meta description"
---


<table id="example" class="display">
    <thead>
        <tr>
            <th>Name</th>
            <th>Position</th>
            <th>Office</th>
            <th>Age</th>
            <th>Start date</th>
            <th>Salary</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Tiger Nixon</td>
            <td>System Architect</td>
            <td>Edinburgh</td>
            <td>61</td>
            <td>2011/04/25</td>
            <td>$320,800</td>
        </tr>
        <!-- Add more rows as needed -->
    </tbody>
</table>


<script>
$(document).ready(function() {
    $('#example').DataTable();
});
</script>
