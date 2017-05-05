# Graphene.css

break out of the grid

## Install

    npm install graphene.css
    
or

    bower install graphene.css

## Build
### `.container`

    <div class="container">...</div>

### `.row`

    <div class="container">
        <div class="row">...</row>
    </div>

### `.col-*`

    <div class="container">
        <div class="row">
            <div class="col-1">...</div>
            <div class="col-11">...</div>
        </row>

        <div class="row">
            <div class="col-6">...</div>
            <div class="col-6">...</div>
        </row>

        <div class="row">
            <div class="col-4">...</div>
            <div class="col-8">...</div>
        </row>
    </div>

### `.row .gutters`

    <div class="container">
        <div class="row gutters">
            <div class="col-6">...</div>
            <div class="col-6">...</div>
        </row>
    </div>

### `.col-* .break-*`

    <div class="container">
        <div class="row">
            <div class="col-4">...</div>
            <div class="col-4 break-2">...</div>
        </row>

        <div class="row">
            <div class="col-6">...</div>
            <div class="col-6 break-1">...</div>
        </row>

        <div class="row">
            <div class="col-9">...</div>
            <div class="col-6 break-3">...</div>
        </row>
    </div>

### `.col-* .push-*`

    <div class="container">
        <div class="row">
            <div class="col-10 push-1">...</div>
        </row>

        <div class="row">
            <div class="col-3 push-1">...</div>
            <div class="col-3 push-1">...</div>
            <div class="col-3 push-1">...</div>
        </row>

        <div class="row">
            <div class="col-4 push-6">...</div>
        </row>
    </div>
