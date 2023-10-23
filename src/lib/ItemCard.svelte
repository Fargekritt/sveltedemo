<script>
import demo from "../assets/demo.png";
export let item = {
    description: "Demo item",
    name: "Demo name",
    imageSrc: demo
};
</script>

<div>
    <img src={item.imageSrc} alt="Demo"/>
    <h2>{item.name}</h2>
    <p>{item.description}</p>
</div>

<style>
    div {
        display: inline-block;
        border: black solid 1px;
        margin-right: 10px;
        padding: 10px;
    }
</style>