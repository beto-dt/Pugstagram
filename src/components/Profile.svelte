<script>
export let nickname;
export let name;
</script>
<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>
<div class="Profile">
    <div class="Profile-content">
      <div class="Profile-avatar">
        <img src="https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/93061657_218061376075765_336509115683569664_o.jpg?_nc_cat=102&_nc_sid=09cbfe&_nc_eui2=AeFGXs1gfZ93vTjNHaU6Lyu5hdqhUC2obj2F2qFQLahuPdVgqPAEUjKXdX7UjYWXwGl8xBwHdsuZmm9eJXyHjTWz&_nc_ohc=q_LaHjKaZfAAX_1Ajji&_nc_ht=scontent.fuio1-1.fna&oh=73ce69fa354067ebcc86420386c2809c&oe=5F10EEC5" alt="" />
      </div>
      <div class="Profile-info">
        <h2>{nickname}</h2>
        <span>{name}</span>
      </div>
    </div>
</div>