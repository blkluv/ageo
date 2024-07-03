<template>
    <footer>
        <div>
            <div>
                <v-btn
                    icon
                    color="#FFFFFF"
                    href="https://discord.gg/K8URcAM2qz"
                >
                    <v-icon size="30">
                        mdi-discord
                    </v-icon>
                </v-btn>
                <v-btn
                    icon
                    color="#FFFFFF"
                    href="https://twitter.com/atl5d"
                >
                    <v-icon size="30">
                        mdi-twitter
                    </v-icon>
                </v-btn>
                <v-btn
                    icon
                    color="#FFFFFF"
                    href="https://www.instagram.com/atlga5d"
                >
                    <v-icon size="30">
                        mdi-instagram
                    </v-icon>
                </v-btn>
                <v-btn
                    icon
                    color="#FFFFFF"
                    href="https://www.tiktok.com/@atl5d"
                >
                    <v-icon size="30">
                        mdi-tiktok
                    </v-icon>
                </v-btn>
            </div>
            <div>
                <p>
                    {{ version }} - {{ $t('Footer.under') }}
                    <a
                        href="https://atl5d.com"
                    >ATL5D</a>
                </p>
            </div>
            <div>
                <a href="https://geo.atl5d.com">{{ $t('Header.about') }}</a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    computed: {
        version() {
            return require('../../../package.json').version;
        },
    },
};
</script>

