<template>
  <div>
    <sidenav-items-section name="Apps">
      <sidenav-item title="All Apps" to="/">
        <all-apps-icon />
      </sidenav-item>
      <sidenav-item title="Updates" to="/admin/updates">
        <updates-icon />
      </sidenav-item>
    </sidenav-items-section>

    <sidenav-items-section name="Categories">
      <sidenav-item title="Photography" to="/admin/photography">
        <photography-icon />
      </sidenav-item>
      <sidenav-item title="Graphic Design" to="/admin/graphic-design">
        <graphic-design-icon />
      </sidenav-item>
      <sidenav-item title="Videos" to="/admin/videos">
        <videos-icon />
      </sidenav-item>
      <sidenav-item title="Illustration" to="/admin/illustration">
        <illustration-icon />
      </sidenav-item>
      <sidenav-item title="UI/UX" to="/admin/ux">
        <ux-icon />
      </sidenav-item>
      <sidenav-item title="3D/AR" to="/admin/ar">
        <ar-icon />
      </sidenav-item>
    </sidenav-items-section>

    <sidenav-items-section name="Guides">
      <sidenav-item title="Documentation" to="/admin/documentation">
        <documentation-icon />
      </sidenav-item>
    </sidenav-items-section>
  </div>
</template>

<script>
import SidenavItem from './Item.vue';
import SidenavItemsSection from './Section.vue';

/* ICONS */
import UxIcon from './icons/Ux.vue';
import ArIcon from './icons/Ar.vue';
import VideosIcon from './icons/Videos.vue';
import AllAppsIcon from './icons/AllApps.vue';
import UpdatesIcon from './icons/Updates.vue';
import PhotographyIcon from './icons/Photography.vue';
import IllustrationIcon from './icons/Illustration.vue';
import GraphicDesignIcon from './icons/GraphicDesign.vue';
import DocumentationIcon from './icons/Documentation.vue';

export default {
  name: 'SidenavItems',
  components: {
    ArIcon,
    UxIcon,
    VideosIcon,
    UpdatesIcon,
    AllAppsIcon,
    SidenavItem,
    PhotographyIcon,
    IllustrationIcon,
    DocumentationIcon,
    GraphicDesignIcon,
    SidenavItemsSection,
  },
};
</script>
