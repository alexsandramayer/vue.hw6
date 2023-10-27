<template>
	<IndexPage/>
	<BlogPage/>
	<BlogDetailsPage/>
	<ProjectPage/>
</template>

<script>
import IndexPage from './components/IndexPage.vue';
import BlogPage from './components/BlogPage.vue';
import BlogDetailsPage from './components/BlogDetailsPage.vue';
import ProjectPage from './components/ProjectPage.vue';


export default { 
	components: {
		IndexPage,
		BlogPage,
		BlogDetailsPage,
		ProjectPage
	},
};
</script>

<style lang="scss">
</style>
