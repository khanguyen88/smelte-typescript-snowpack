<script lang='typescript'>
    import Button from 'smelte/src/components/Button';
    import TextField from 'smelte/src/components/TextField';
    import './smelte.copy.css';
</script>

<div class="h-screen flex w-full">
    <form class="w-1/2 m-auto">
        <TextField label="Username" outlined/>
        <TextField label="Password" outlined type="password"/>
        <Button>Login</Button>
    </form>
</div>
