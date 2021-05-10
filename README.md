<!DOCTYPE html>
<html>
    <head>
        <title>Registrasi</title>
    </heaad>
    <body>
        <form action="Praktikum7_Web1.php" method="POST">
            <Fieldset>
                <h1>Form Input Data Pegawai</h1>
            <p>
                <label>Nama Pegawai :</label>
                <input type="text" name="nama">
            </p>
            <p>
                <label>Tanggal lahir :</label>
                <input  name="tanggal_lahir">
            </p>

            <p>
                <label>Jenis pegawai :</label>
                <select name="jenis_pegawai">
                    <option value="Kontrak">Kontrak</option>
                    <option value="Tetap">Tetap</option>
                </select>
            </p>
            <p>
                <label>Posisi :</label><br>
                <label><input type="radio" name="job" value="Operator">Operator</label>
                <label><input type="radio" name="job" value="Leader">Leader</label>
                <label><input type="radio" name="job" value="Supervisor">Supervisor</label>
            </p>
            <p>
                <label>Total jam kerja : </label>
                <input type="number" name="jam_kerja"/>
            </p>
            <p>
                <input type="submit" name="submit" value="Hitung"/>
            </p>
            </fieldset>
        </form>
</body>
</html>
