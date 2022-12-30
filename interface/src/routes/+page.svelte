<script>
	
    import { page } from '$app/stores';
    import supabase from "./supa";
    import { goto } from "$app/navigation";
    
</script>

<body style="background-color: darkolivegreen;">
    <h1>Welcome to SuperBursary</h1>
    <h3>Are you curently studying in university and looking for a Bursary? Well you have come to the right place!</h3>
    <h3>Apply online today</h3>
    <p>Before you apply please make sure you have the the required documents</p>
    <pre>
- Certified ID
- Proof of residence
- Proof of registration
- Latest university report
    </pre>
    <a href="\CreatePage">Create Account</a>
    <br><br>
    <a href="\SignInPage">Sign In</a>
</body>

