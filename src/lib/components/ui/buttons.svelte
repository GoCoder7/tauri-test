<script>
  import { Button } from "./button";
  import Mail from "lucide-svelte/icons/mail";
  import Chevronright from "lucide-svelte/icons/chevron-right";
  import { LoaderCircle } from "lucide-svelte";
</script>

<h1>Buttons</h1>
<div class="flex flex-col items-center">
  <Button>default</Button>
  <Button variant="secondary">secondary</Button>
  <Button variant="destructive">destructive</Button>
  <Button variant="outline">outline</Button>
  <Button variant="ghost">ghost</Button>
  <Button variant="link">link</Button>
  <Button disabled>
    <LoaderCircle class="mr-2 h-4 w-4 animate-spin" />
    loading animation(disabled)
  </Button>
  <Button>
    <Mail class="mr-2 h-4 w-4" />
    Button with Icon
  </Button>
  <div>
    <Button variant="outline" size="icon">
      <Chevronright class="h-4 w-4" />
    </Button>
    size="icon"
  </div>
</div>
