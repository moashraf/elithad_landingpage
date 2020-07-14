<template>
  <div>
    <b-modal id="modal-center" centered title="تواصل معنا لتعرف المزيد">
      <form id="app" action="https://elithad.com/landingpage/go.php"  method="post">
        <div>
          <label for="name"></label>
          <input
            id="name"
            required
            class="form-control"
            placeholder="الأسم"
            v-model="name"
            type="text"
            name="name"
          />
        </div>

        <div>
          <input
            id="email"
            required
            class="form-control"
            placeholder="البريد الألكتروني"
            v-model="email"
            type="email"
            name="email"
            min="0"
          />
        </div>

        <div>
          <input
            id="phone"
            required
            class="form-control"
            placeholder="رقم الهاتف"
            v-model="phone"
            type="tel"
            name="phone"
            min="0"
          />
        </div>

        <div>
          <textarea
            id="msg"
            class="form-control"
            placeholder="الرسالة"
            v-model="msg"
            type="text"
            name="msg"
            min="0"
          />
        </div>

        <div>
          <input type="submit" class="btn btn-success" value=" ارسال" />
        </div>
      </form>
    </b-modal>
  </div>
</template>

<script>
export default {
  name: "Form",
  data: function() {
    return {
      errors: [],
      name: null,
      email: null,
      phone: null,
      msg: null
    };
  }
};
</script>
