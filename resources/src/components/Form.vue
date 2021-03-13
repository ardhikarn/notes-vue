<template>
  <div class="formNotes">
    <div class="menu">
      <button type="button" class="bg-danger btn btn-delete">Hapus</button>
      <button type="submit" class="bg-success btn btn-submit">Simpan</button>
    </div>

    <div class="content">
      <input type="text" class="text" placeholder="Title" />
      <textarea
        type="text"
        class="text text-area"
        placeholder="Tulis Notemu"
      ></textarea>
    </div>
  </div>
</template>

<style>
.menu {
  background: #f7f7f7;
  padding: 10px 25px;
  margin-bottom: 25px;
  text-align: right;
  border-bottom: 1px solid #e8e6e6;
}
.btn-delete {
  margin-right: 10px;
}
.content {
  padding: 0px 25px;
}
.text {
  display: block;
  width: 100%;
  padding: 0px;
  font-size: 20px;
  font-weight: bold;
  color: #2c3e50;
  border: none;
  margin-bottom: 10px;
  box-sizing: border-box;
  outline: none;
}
.textarea {
  min-height: 350px;
  font-size: 15px;
  font-weight: lighter;
  line-height: 30px;
}
.loader {
  vertical-align: middle;
}
</style>
