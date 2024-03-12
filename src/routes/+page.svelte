<script>
    import Card from '../components/card.svelte'
    import Avatar from '../components/avatar.svelte'
    import Button from '../components/button.svelte'
    import Icon from '../components/icon.svelte';
    import Nav from '../components/Nav.svelte';
    import ProfileInfo from '../components/ProfileInfo.svelte';
    import Title from '../components/Title.svelte';
    import Timeline from '../components/Timeline.svelte';
  
  </script>
  
  <!-- <Card imgSrc='pc.jfif' text='No amount of technology can convert a bad story into a good story.' /> -->
  <!-- <Avatar /> -->
  <!-- <Button /> -->
  <!-- <Icon /> -->
  <!-- <Title /> -->
  <div class="mqx-[117px] mx-[7%] max-w-[1658px] xl:mx-auto">
  <Nav />
  <ProfileInfo />
  <Timeline />
  </div>
    
  <style lang="postcss">
  
    .con {
        margin: 0 117px;
    }
  
  
  
    :global(html) {
        font-family: 'Inter';
    }
  
  </style>