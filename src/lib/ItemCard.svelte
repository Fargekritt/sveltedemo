<script>
import demo from "../assets/demo.png";
export let item;
</script>

<div>
    <img src={demo} alt="Demo"/>
    <h2>{item}</h2>
    <p>Dette er demo tekst</p>
</div>

<style>
    div {
        display: inline-block;
        border: black solid 1px;
        margin-right: 10px;
        padding: 10px;
    }
</style>