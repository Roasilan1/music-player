<template>
      <div class="header-profile">
        <div class="notification">
          <span class="notification-number">3</span>
          <svg
            viewBox="0 0 24 24"
            fill="currentColor"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-bell"
          >
            <path
              d="M18 8A6 6 0 006 8c0 7-3 9-3 9h18s-3-2-3-9M13.73 21a2 2 0 01-3.46 0"
            />
          </svg>
        </div>
        <svg viewBox="0 0 512 512" fill="currentColor">
          <path
            d="M448.773 235.551A135.893 135.893 0 00451 211c0-74.443-60.557-135-135-135-47.52 0-91.567 25.313-115.766 65.537-32.666-10.59-66.182-6.049-93.794 12.979-27.612 19.013-44.092 49.116-45.425 82.031C24.716 253.788 0 290.497 0 331c0 7.031 1.703 13.887 3.006 20.537l.015.015C12.719 400.492 56.034 436 106 436h300c57.891 0 106-47.109 106-105 0-40.942-25.053-77.798-63.227-95.449z"
          />
        </svg>
        <img class="profile-img" src="../../images/头像.jpg" alt="" />
      </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.header-profile{
    display: flex;
    align-items: center;
    padding: 0 16px 0 40px;
    margin-left: auto;
    flex-shrink: 0;
}
.profile-img {
    width: 32px;
    height: 32px;
    border-radius: 50%;
    -o-object-fit: cover;
    object-fit: cover;
    border: 2px solid var(--theme-color);
    margin-left: 22px;
    cursor: pointer;
}
.header-profile svg {
    width: 22px;
    color: #f9fafb;
    flex-shrink: 0;
}
.notification+svg {
    margin-left: 22px;
}
@media screen and (max-width: 945px) {
    .notification+svg {
        display: none;
    }
}
</style>