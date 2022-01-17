<template>
<CNavbar expand="lg" color-scheme="dark" class="bg-dark">
  <CContainer fluid>
    <CNavbarBrand href="#">
          <img src="/images/logo.png" alt="" width="40" height="40"/>
</CNavbarBrand>
    <CNavbarToggler aria-label="Toggle navigation" aria-expanded={visible} @click="visible = !visible"/>
    <CCollapse class="navbar-collapse" :visible="visible">
      <CNavbarNav>
        <CNavItem>
          <CNavLink href="#" active>
            Home
          </CNavLink>
        </CNavItem>
         <CDropdown variant="nav-item" :popper="false">
          <CDropdownToggle color="secondary">Acadmics</CDropdownToggle>
          <CDropdownMenu>
            <CDropdownItem href="#">Action</CDropdownItem>
            <CDropdownItem href="#">Another action</CDropdownItem>
            <CDropdownDivider />
            <CDropdownItem href="#">Something else here</CDropdownItem>
          </CDropdownMenu>
        </CDropdown>
         <CDropdown variant="nav-item" :popper="false">
          <CDropdownToggle color="secondary">Student Life</CDropdownToggle>
          <CDropdownMenu>
            <CDropdownItem href="#">Action</CDropdownItem>
            <CDropdownItem href="#">Another action</CDropdownItem>
            <CDropdownDivider />
            <CDropdownItem href="#">Something else here</CDropdownItem>
          </CDropdownMenu>
        </CDropdown>
         <CDropdown variant="nav-item" :popper="false">
          <CDropdownToggle color="secondary">Facilities</CDropdownToggle>
          <CDropdownMenu>
            <CDropdownItem href="#">Action</CDropdownItem>
            <CDropdownItem href="#">Another action</CDropdownItem>
            <CDropdownDivider />
            <CDropdownItem href="#">Something else here</CDropdownItem>
          </CDropdownMenu>
        </CDropdown>
       <CNavItem class="position-absolute top-2 end-0 d-flex">
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
