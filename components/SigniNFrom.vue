<template>
  <div>
    <v-card class="mx-auto" prepend-icon="$vuetify" subtitle="" width="auto">
      <template v-slot:title>
        <span class="font-weight-black">โปรดลงชื่อเข้าใช้</span>
      </template>

      <v-card-item class="bg-cyan-darken-3">
        <v-card-tile class="font-weight-bold pa-3">
          <v-icon class="fas fa-right-to-bold-bracket mr-2"></v-icon>
          กรอกข้อมูลเพื่อ เข้าสู่ระบบ
        </v-card-tile>
      </v-card-item>

      <v-card-text class="pa-8">
        <v-form>
          <v-row>
            <v-col cols="12">
              <v-text-field label="ชื่อผู้ใช้" variant="outlined"></v-text-field>
            </v-col>


            <v-col cols="12">
              <v-text-field type="password" label="รหัสผ่าน"></v-text-field>
            </v-col>

            <v-col cols="12" class="text-center">
              <v-btn color="success" class="w-100 w-md-75">เข้าสู่ระบบ</v-btn>

            </v-col>
          </v-row>
        </v-form>
      </v-card-text>
    </v-card>


  </div>
</template>