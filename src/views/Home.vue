<template>
  <div class="home">
    <div class="container">
      <form>
        <!-- <div class="form-group">
          <label for="prefix">Title</label>
          <select name="salutation" id="prefix" class="form-control">
            <option value="" id="">Prefix</option
            ><option value="Mr." id="Mr.">Mr.</option
            ><option value="Ms." id="Ms.">Ms.</option
            ><option value="Mrs." id="Mrs.">Mrs.</option
            ><option value="Miss" id="Miss">Miss</option
            ><option value="Dr." id="Dr.">Dr.</option></select
          >
          <span
            class="field-validation-error"
            data-valmsg-for="prefix"
            data-valmsg-replace="true"
          >
            <span id="prefix-error" class=""></span>
          </span>
        </div> -->
        <!-- <div class="form-group">
          <label for="fname">First Name *</label>
          <input
            type="text"
            id="fname"
            name="fname"
            class="form-control"
            placeholder="First Name"
            maxlength="99"
          />
          <span
            class="field-validation-error"
            data-valmsg-for="First_Name"
            data-valmsg-replace="true"
          >
            <span id="fname-error" class=""></span>
          </span>
        </div> -->
        <!-- <div class="form-group">
          <label for="lname">Last Name *</label>
          <input
            type="text"
            id="lname"
            name="lname"
            class="form-control"
            placeholder="Last Name"
            maxlength="99"
          />
          <span
            class="field-validation-error"
            data-valmsg-for="Last_Name"
            data-valmsg-replace="true"
          >
            <span id="lname-error" class=""></span>
          </span>
        </div> -->
        <div class="form-group dob">
          <label for="">Date of Birth *</label>
          <div class="input-wrapper">
            <input
              type="text"
              id="loginDatePicker"
              name="loginDatePicker"
              class="form-control hasDatepicker"
              autocomplete="off"
              placeholder="mm/dd/yyyy"
            />

            <span
              class="field-validation-error"
              data-valmsg-for="Date_of_Birth"
              data-valmsg-replace="true"
            >
              <span id="loginDatePicker-error" class=""></span>
            </span>
            <i class="fa fa-calendar"></i>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
  import "./Home.scss";
  export default {
    name: "Home"
  };
</script>

// <style lang="scss"></style>
