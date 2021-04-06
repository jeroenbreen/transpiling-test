<script>
export default {
    name: 'Sticky',
    components: {},
    computed: {},
    methods: {}
}
</script>


<template>
    <div class="Sticky example">
        <div class="example__head">
            2) CSS: Sticky
        </div>
        <div class="example__caniuse">
            <a href="https://caniuse.com/css-sticky" target="_blank">
                https://caniuse.com/css-sticky
            </a>
        </div>
        <div class="example__body">
            <div class="Sticky__container">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer mattis iaculis odio, in venenatis libero scelerisque a. Sed accumsan interdum dui ac vehicula. Pellentesque viverra a purus id bibendum. Duis pellentesque varius ante ut maximus. Curabitur finibus tortor nisi, ac cursus ex pellentesque et. Aliquam eu mauris nec massa hendrerit condimentum. Aenean blandit egestas lorem, sed elementum enim pulvinar elementum.

                <div class="Sticky__sticky">
                    This is sticky!
                </div>
                Nulla sed malesuada neque. Praesent sagittis nunc nulla, eu vestibulum lacus venenatis sed. Nulla sollicitudin, ex non varius cursus, risus neque vulputate sapien, ac elementum erat risus ac tellus. Duis tristique, ligula quis placerat luctus, massa est tincidunt lacus, fermentum iaculis odio ex nec neque. Integer convallis nisi libero, sit amet facilisis nisl vestibulum sed. Cras lacinia nunc quis metus fermentum venenatis vel at arcu. Donec in accumsan elit. Donec purus neque, volutpat id libero nec, pretium iaculis dolor. Nam et egestas ex. Integer semper eget orci id consequat. Aliquam a metus nec enim varius commodo. Suspendisse consectetur dolor elementum, ornare quam sed, volutpat diam.

                Sed finibus eget mi at aliquet. Pellentesque sit amet pretium magna. Praesent feugiat nisi molestie magna elementum consequat. Aliquam erat volutpat. In facilisis at augue id consequat. Nam molestie, odio ut tempus semper, lorem nunc molestie dui, eget placerat erat arcu vel est. Sed pharetra lobortis elit, id pharetra libero semper eget. Nulla sit amet nulla auctor, egestas ante sed, dignissim lorem. Interdum et malesuada fames ac ante ipsum primis in faucibus. Suspendisse sagittis eu sapien sed efficitur. Mauris sed neque porttitor, eleifend ex sed, pulvinar urna. Etiam gravida mauris molestie quam feugiat, sit amet porta nunc pretium.

                Cras at tincidunt lorem. Aenean ut lobortis dui. Aliquam erat volutpat. Nam mollis vulputate ipsum vel efficitur. Etiam varius justo mi. Quisque sit amet lorem sem. Mauris vitae metus laoreet, elementum velit quis, facilisis nisl. Duis lacinia ex eget ex aliquam elementum. Sed posuere quis felis vel dapibus. Suspendisse semper nibh est, et eleifend eros sagittis vel. Sed auctor arcu purus, dictum dapibus ligula consequat vitae. Curabitur venenatis libero ac quam pretium, pulvinar facilisis nunc dapibus. Suspendisse ullamcorper pulvinar ex, ut finibus tellus laoreet faucibus.

                Fusce vehicula lacus eget congue vestibulum. Nulla vitae pharetra quam, at ullamcorper dolor. Suspendisse suscipit quam eu rhoncus tristique. Nulla a mollis ligula, id porttitor ante. Duis congue enim ex, nec ornare erat ornare a. Phasellus erat libero, interdum vitae lorem ut, accumsan mattis enim. Nunc eu est id tortor dapibus maximus. Duis eget facilisis nisl. Suspendisse potenti. Nunc vitae viverra mauris. Proin faucibus facilisis risus sit amet fringilla. Vestibulum venenatis diam non convallis scelerisque. Vestibulum quis pretium ligula. Nullam id dolor et lectus dignissim euismod. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sit amet consectetur nibh.
            </div>
        </div>
    </div>
</template>


<style lang="scss">
    .Sticky {

        .Sticky__container {
            width: 200px;
            height: 200px;
            overflow: auto;

            .Sticky__sticky {
                background: pink;
                padding: 8px;
                margin: 12px 0;
                position: -webkit-sticky; /* Safari */
                position: sticky;
                top: 8px;
            }
        }
    }
</style>
