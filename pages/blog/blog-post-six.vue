<template>
    <div class="col-md-6 m-auto">
        <div class="card gradient-layout">
            <div class="card-header">
                <div class="card-title">
            <h1>Custom Layouts.....</h1>
                </div>
                <div class="card-body">
            <p class="card-text">
                Under the script tag, we import the layout of our choice
        
                <code>
                    \<\script\>\
        export default {
            layout : 'blogs'
            }
        \</>\</code> 
            </p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis nesciunt laboriosam veniam iste culpa rerum inventore, corrupti facilis quasi incidunt ab porro repellendus architecto velit atque quam asperiores alias commodi!</p>
        
                </div>
                <div class="card-footer">
                    Authored By Gh0stXps 
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    layout : 'blogs'
    }
</script>