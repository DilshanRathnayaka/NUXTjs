<template>
<div><a href="/dashboard"><button class="btn btn-outline-danger fw-bold fs-6 rounded-pill mt-3" >Back</button></a>
 <center><div class="fw-bold fs-2 rounded-pill ">Products</div></center>
 <div class="p-5">
 <table class="table mt-5 p-4">
        <thead class=" bg-info fw-bold">
        <th>Product ID</th>
            <th>Product Name</th>
            <th>Product Price</th>
            <th>Product Status</th>
            <th>Product Image</th>
            <th>Update</th>
            <th>Delete</th>
        </thead>
        <tbody>
               <tr>
                  <td>5</td>
                  <td>School Bag</td>
                  <td>2000</td>
                  <td>Active</td>
                  <td><img src="https://i.ibb.co/8KJ3xp1/71x-MWMGpo9-S.jpg" alt="" class="" width="100px" height="100px"></td>
                  <td class="pt-5"><input type="submit" value="Update" class="btn btn-outline-info rounded-pill"></td>
                <td class="pt-5"><input type="submit" value="Delete" class="btn btn-outline-info rounded-pill"></td>
                </tr>
            
        </tbody>
      
     </table></div>
 
 
 
 
 
 </div>

  

</template>

<script>
export default {
  name: 'IndexPage'
}

</script>
