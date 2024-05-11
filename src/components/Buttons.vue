<template>
  <div class="buttons">
    <div>
      <a target="_blank" href="https://twitter.com/ElricLiu_007"><button>
        <img :src="twitter" />
        Follow Me
      </button></a>
      <a target="_blank" href="https://buymeacoffee.com/elricliu" style="margin-left: 10px;"><button>
        <img :src="coffee" />
        By me coffee
      </button></a>
    </div>
    <div style="margin-top: 20px">
      <div>❤️ Sponsor</div>
      <a target="_blank" href="https://gptscopilot.ai/?utm_source=ugly-face"><button>GPTs Copilot</button></a>
    </div>
  </div>
</template>

<script>
import twitter from '@/assets/icons8-推特.gif'
import coffee from '@/assets/icons8-咖啡杯.gif'

export default {
  name: "Buttons",
  data() {
    return {
      twitter,
      coffee,
    }
  },
  methods: {
  },
  mounted() {
  },
};
</script>

<style scoped>
.buttons {
  width: 500px;
  position: absolute;
  top: calc(50% + 370px);
  left: 50%;
  transform: translate(-50%, -50%);
  /* center items vertically */
  justify-content: center;
  background-color: #ffffff;
  padding: 5px;
}
button {
  margin-top: 10px;
  width: 200px;
  padding: 5px;
  background: transparent;
  border-width: 2px;
  font-size: 15px;
  border-color: black;
  color: black;
  font-weight: bold;
  user-select: none;
  border-radius: 10px;
  box-shadow: 2px 2px 0px 0px rgba(0, 0, 0, 0.75);
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

button img {
  width: 18px;
  height: 18px;
  margin-right: 8px;
}

button:hover {
  background: black;
  color: white;
  transition: 0.3s;
}
button:active {
  background: rgb(65, 65, 65);
  box-shadow: 1px 1px 0px 0px rgba(0, 0, 0, 0.75);
}
</style>
