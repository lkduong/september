<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">YouTube Component</div>

                    <div class="card-body">
                        <iframe id="player" type="text/html" width="640" height="390"
  src="http://www.youtube.com/embed/hqxhKQznPuo?enablejsapi=1&origin=http://example.com"
  frameborder="0"></iframe>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.');
        }
    }
</script>
