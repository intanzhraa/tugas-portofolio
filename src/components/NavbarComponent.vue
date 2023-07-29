<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://cdn.icon-icons.com/icons2/2436/PNG/512/info_icon_147458.png">
          Portofolio Intan Zahra Putri
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">BERANDA</NavbarLink>
          <NavbarLink link="#">TENTANG</NavbarLink>
          <NavbarLink link="#">RIWAYAT PENDIDIKAN</NavbarLink>
          <NavbarLink link="#">SKILL</NavbarLink>
          <NavbarLink link="#">PRESTASI DAN PENGALAMAN</NavbarLink>
          <NavbarLink link="#">KONTAK</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
