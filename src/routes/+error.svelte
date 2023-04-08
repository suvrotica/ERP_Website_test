<script>
    import { page } from "$app/stores";
</script>

<div class="d-flex align-items-center justify-content-center vh-50 bg-primary">
    <h4 class="display-1 fw-bold text-white">
        {$page.status}:{$page.error?.message}
    </h4>
</div>
