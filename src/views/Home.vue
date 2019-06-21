<template>
  <div class="home">
    <div class="container mx-auto p-4 text-center">
      <div class="w-full md:w-4/5 lg:w-3/5 mx-auto">

        <h1 class="font-hand text-4xl uppercase mb-3">Hello</h1>

        <p>You may have seen me around the school, taking a child out of class, along the corridors or play grounds. Therefore I would like to take this opportunity to introduce myself to you.</p>
        <p>My name is Henrieta and I look like this:</p>

        <div class="flex flex-col md:flex-row justify-center items-center my-16">
          <img class="w-48 mb-12 md:mr-12 md:mb-0 border border-teal-400 rounded-full" src="@/assets/Hena.png" alt="">
          <img class="w-48 border border-teal-400 rounded-full" src="@/assets/hena_color.jpg" alt="">
        </div>

        <p>I am a Psychotherapist with <a class="text-blue-600 hover:text-blue-800" href="https://www.liverpoolcamhs.com/support/seedlings/" target="_blank">Seedlings</a>.</p>
        <p>Seedlings is a CAMHS therapeutic service based in schools around Liverpool. Delivered in partnership with PSS and YPAS, the Seedlings team work with children and young people and their families to explore and process feelings that are troubling them. We provide one to one and group therapy to support young people’s mental health and wellbeing.</p>
        <p>My primary training is in Movement Psychotherapy, which is based on an understanding of the connections between body, mind and emotions. It is one of the creative arts therapies. This means that I pay extra attention to the way children express their feelings unconsciously through movements, tensions, behaviours or aches. I use different tools, such as body awareness, conscious reflections, creativity or mindfulness, to help children and people around them understand and gain some control over feelings that might trouble them.</p>
        <p>Please feel free to pop in and see me when I am in your school.</p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    // HelloWorld
  }
};
</script>
