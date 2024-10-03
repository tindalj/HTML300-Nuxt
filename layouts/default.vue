<template>
    <div>
        <header>
            <nav>
                <ul>
                    <li>
                    <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li>
                    <NuxtLink to="/blog">Blog</NuxtLink>
                    </li>
                </ul>
            </nav>
        </header>
        <slot />
    </div>
</template>