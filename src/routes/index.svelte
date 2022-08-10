<script lang="ts">
  export let now: string;

  console.log(now.toString(), (now as any) instanceof Date,typeof now === 'string');
</script>

<h1>Check server and browser log</h1>
