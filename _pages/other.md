---
title: Other Things of Interest
layout: single
---

## McMaster Thesis Template

I maintain a LaTeX version of the McMaster Thesis template. This template should cover the general specifications for both Masters and Ph.D. thesis formats. Some tweaking may be necessary, but this provides most of the general layout and has been used my many M.Sc. and Ph.D. students already.

The most recent version available from my [GitHub repo](https://github.com/benjaminfurman/McMaster_Thesis_Template).

An occasionally updated version is available in the [Overleaf templates gallery](https://www.overleaf.com/latex/templates/mcmaster-thesis-example/bjccppctqwgt#.V_wpQNxD9E4).


## A link just for me

Don't you worry about what this leads to.

<body>
Enter password: <input id='password' type='text'  />
<a href="/_pages/test_protected/" onclick="javascript:return validatePass()">enter your password and click this</a>
<script>
function validatePass(){
    if(document.getElementById('password').value == 'yourBussinessCardPassword'){
        return true;
    }else{
        alert('wrong password!!');
        return false;
    }
}
</script>
</body>
