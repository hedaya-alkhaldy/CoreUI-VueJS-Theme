<template>
<CNavbar expand="lg" color-scheme="dark" class="bg-dark">
  <CContainer fluid>
    <CNavbarBrand href="#">Navbar</CNavbarBrand>
    <CNavbarToggler aria-label="Toggle navigation" aria-expanded={visible} @click="visible = !visible"/>
    <CCollapse class="navbar-collapse" :visible="visible">
      <CNavbarNav>
        <CNavItem>
          <CNavLink href="#" active>
            Home
          </CNavLink>
        </CNavItem>
        <CNavItem>
          <CNavLink href="#">Features</CNavLink>
        </CNavItem>
        <CNavItem>
          <CNavLink href="#">Pricing</CNavLink>
        </CNavItem>
       <CNavItem class="position-absolute top-0 end-0 d-flex">
        <CNavLink href="/login">Login</CNavLink>
        <CNavLink href="/register">Register</CNavLink>
        </CNavItem>
      </CNavbarNav>
    </CCollapse>
  </CContainer>
</CNavbar>
</template>
<script>

export default ({
 name:"Nav",

})

</script>
