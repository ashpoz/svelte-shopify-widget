<script lang="ts">
  const handleSubmit = () => {
    console.log("add to cart");
  };
</script>

<form on:submit|preventDefault={handleSubmit}>
  <select name="Size" id="">
    <option value="Small">Small</option>
    <option value="Medium">Medium</option>
    <option value="Large">Large</option>
  </select>
  <select name="Color" id="">
    <option value="Blue">Blue</option>
    <option value="Black">Black</option>
  </select>
  <input type="submit" value="Add to Cart" />
</form>
